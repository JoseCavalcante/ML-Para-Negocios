<b>Estudo de Caso</b>
<p>Departamento de Manutenção e Produção</p>

<p>Para este estudo de caso utilizaremos técnicas avançadas de DEEP LEARNING e REDES NEURAIS para fazermos a detecção de peças defeituosas e também vamos localizar ou segmentar os problemas nas peças.</p>

<img src="" alt="imagem/>

<p>Nós podemos visualizar este funcionário que está fazendo a análise de vários componentes.</p>
<p>Temos uma IA (cérebro)</p>
<p>E o objetivo é aplicar algoritmos inteligentes para poder detectar peças defeituosas.</p>
<p>Este estudo de caso é considerado bem avançado pelo fato de ter que se criar 2 modelos:</p>
<p>O 1o Modelo vai precisar fazer a <b>identificação</b> se uma imagem apresenta ou não um defeito.</p>
<p>Se o defeito for dectado vai ser necessário vamos ter de aplicar outro modelo de DEEP LEARNIG para poder separar um defeito na imagem.</p>
<p>Isso também pode usado naarea de medicina.</p>
<p>A IA e ML estão transformando a industria, principalmente os departamento de produção e manutenção.</p>
<p>De acordo com o relátorio do WORLD ECONOMIc FORUM, essas tecnologias terão grande impacto na INDUSTRIA 4.0: Departamento de Produção, Manutenção e de Suprimentos</p>
<p>As técnicas de DEEP LEARNING tem provado serem eficientes para detecção e localização de defeitos em imagens. https://landing.ai/industries/medical-devices/</p>

CLASSIFICAÇÃO e SEGMENTAÇÃO

Conceitos

<p>É necessário entender o formato que a SEGMENTAÇÃO das imagens é definido pois como nós temos 2 tarefas:</p>
<p>1 - Identificar se tem defeito </p>
<p>2 - A localização do defeito na imagem</p>
<p>Nós precisamos ter uma representação um pouco diferente:</p>
<p>MASK(Máscara)</p>
<p>O objetivo da segmentação de imagem é entender a imagem pixel a pixel, sendo que cada pixel é associado a uma classe.</p>
<p>Quando trabalhamos com as redes neurais convolucionais como por exemplo para fazer a classificação de doenças a resposta de Rede Neural será se a pessoa é doente ou não é doente. A imagem do Raio X apresenta uma doenção ou não apresenta uma doenca. É passada uma imagem inteira e se obtem uma resposta da rede neural.</p>
<p>Quando trabalhamos com segmentação de imagens vamos precisar ter uma classificação A, B, C
Vamos supor que temos 4 tipos de defeitos: O defeito 1 é um problema na soldagem da peça e o defeito 2 poderia ser um vazamento de agua. Esses defeitos possuem caracteristicas diferentes na imagem. Portanto, para fazermos a segmentação ou encontrar esses defeitos na imagem nos precisamos analisar cada um dos pixels da imagem. Isso indica que temos um problema de classificação mai complexo pelo fato de que nós precisamos classificar cada pixel.</p>
Por exemplo:
<p>O pixel 1 da imagem não tem defeito. O pixel numero 2 não tem defeito. O pixel 3 tem a caracteristica de ser o defeito do vazamento. O pixel 4 também tem a caracteristica do defeito do vazamento de agua. o pixel 5 nao tem caracteristicas de defeito.
Essa é a idéia de se segmentar imagens.</p>
<p>A saida da segmentação de imagens produz uma nova imagem que é chamada de MASCARA DE IMAGEM que tem esse conceito MASK que é bem importante.</p>
<p>Quando utilizamos Rede Neural Convolucional para classificação de imagens ele vai indicar se a peça tem defeito ou nao tem defeito.</p>
<p>Quando estamos trabalhando com segmentação a Rede Neural vai retornar uma saida que que possui as mesmas dimensões da imagem. </p>
<p>Por exemplo, se a imagem original possui dimensões 800 X 600 a saida da Rede Neural também será uma imagem com as mesmas proporções que é chamada de Mascara de Imagem e a diferença é que so teremos marcados os pixels que possuem defeitos na imagem.
</p>
<br>
RUN LENGHT ENCODING (RLE)




