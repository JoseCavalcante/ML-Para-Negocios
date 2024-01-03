Estudo de Caso
Departamento de Manutenção e Produção

Para este estudo de caso utilizaremos técnicas avançadas de DEEP LEARNING e REDES NEURAIS para fazermos a detecção de peças defeituosas e também vamos localizar ou segmentar os problemas nas peças

<img src="" alt="imagem>

Nós podemos visualizar este funcionário que está fazendo a análise de vários componentes.
Temos uma IA (cérebro)
E o objetivo é aplicar algoritmos inteligentes para poder detectar peças defeituosas.
Este estudo de caso é considerado bem avançado pelo fato de ter que se criar 2 modelos:
O 1o Modelo vai precisar fazer a identificação se uma imagem apresenta ou não um defeito.
Se o defeito for dectado vai ser necessário vamos ter de aplicar outro modelo de DEEP LEARNIG para poder separar um defeito na imagem.
Isso também pode usado naarea de medicina.
A IA e ML estão transformando a industria, principalmente os departamento de produção e manutenção.
De acordo com o relátorio do WORLD ECONOMIc FORUM, essas tecnologias terão grande impacto na INDUSTRIA 4.0: Departamento de Produção, Manutenção e de Suprimentos
As técnicas de DEEP LEARNING tem provado serem eficientes para detecção e localização de defeitos em imagens. https://landing.ai/industries/medical-devices/

CLASSIFICAÇÃO e SEGMENTAÇÃO

Conceitos

É necessário entender o formato que a SEGMENTAÇÃO das imagens é definido pois como nós temos 2 tarefas:
1 - Identificar se tem defeito 
2 - A localização do defeito na imagem
Nós precisamos ter uma representação um pouco diferente:
MASK(Máscara)
O objetivo da segmentação de imagem é entender a imagem pixel a pixel, sendo que cada pixel é associado a uma classe.
Quando trabalhamos com as redes neurais convolucionais como por exemplo para fazer a classificação de doenças a resposta de Rede Neural será se a pessoa é doente ou não é doente. A imagem do Raio X apresenta uma doenção ou não apresenta uma doenca. É passada uma imagem inteira e se obtem uma resposta da rede neural.
Quando trabalhamos com segmentação de imagens vamos precisar ter uma classificação A, B, C
Vamos supor que temos 4 tipos de defeitos: O defeito 1 é um problema na soldagem da peça e o defeito 2 poderia ser um vazamento de agua. Esses defeitos possuem caracteristicas diferentes na imagem. Portanto, para fazermos a segmentação ou encontrar esses defeitos na imagem nos precisamos analisar cada um dos pixels da imagem. Isso indica que temos um problema de classificação mai complexo pelo fato de que nós precisamos classificar cada pixel.
Por exemplo:
O pixel 1 da imagem não tem defeito. O pixel numero 2 não tem defeito. O pixel 3 tem a caracteristica de ser o defeito do vazamento. O pixel 4 também tem a caracteristica do defeito do vazamento de agua. o pixel 5 nao tem caracteristicas de defeito.
Essa é a idéia de se segmentar imagens.
A saida da segmentação de imagens produz uma nova imagem que é chamada de MASCARA DE IMAGEM que tem esse conceito MASK que é bem importante.
Quando utilizamos Rede Neural Convolucional para classificação de imagens ele vai indicar se a peça tem defeito ou nao tem defeito.
Quando estamos trabalhando com segmentação a Rede Neural vai retornar uma saida que que possui as mesmas dimensões da da imagem. Por exemplo, se a imagem original possui dimensões 800 X 600 a saida da Rede Neural também será uma imagem com as mesmas proporções



