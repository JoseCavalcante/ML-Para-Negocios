<p><B>DEPARTAMENTO DE VENDAS</B></p>
<P>Previsão de vendas futuras</P>
<p>Vamos trabalhar com uma Base de Dados com informações sobre a quantidade de vendas e a quantidade de pessoas.</p>
<p>Utlizando dados do passado, o objetivo será fazer previsões de vendas futuras</p>
<p>Essa é a idéia de se trabalhar com <b>séries temporais</b></p>
<p>O diferencial deste estudo é que ele será feito utilizando uma ferramenta do Facebook, o Facebook Prophet, cuja idéia e fazermos previsões de vendas ou previsões de qualquer outro tipo de valor numérico.</p>
<p>Outro diferencial, é que esta ferramenta considera todos os feriados do ano (Pascoa, Natal, BlackFriday etc)(.</p>
<p>As empresas podemm se tornar mais competitivas elas devem fazer uso dessa ferramenta de IA/ML. Podendo, assim, prever seus estoques para poder atender as demandas.</p>
<p>Modelos de previsão de vendas futuras baseados em dados do passado devem considerar EFEITOS SAZONAIS.</p>
<p>Os modelos tradicionais baseados em Séries Temporais não levam em consideração esses fatores</p>
<p>Neste projeto nós vamos atuar como Cientista de Dados de uma rede de lojas físicas.</p>
<p>Tabela das transações de vendas - Descriçãqo das Variáveis</p>
<table>
  <tr>
    <td>
      <table>
        <tr><td>ID</td><td>Identificador da transação (Loja + Data)</td></tr>
        <tr><td>LOJA</td><td>Identificador único da loja</td></tr>
        <tr><td>SALES</td><td>Vendas/Dia (Objetivo)</td></tr>
        <tr><td>CUSTOMERS</td><td>Número de clientes/dia</td></tr>
        <tr><td>OPEN</td><td>Boolean que indica se a loja estava Aberta ou Fechada</td></tr>
        <tr><td>PROMO</td><td>Indica se existia uma promoção naquele dia</td></tr>
        <tr><td>SATATEHOLIDAY</td><td>Feriado (a = Feriado público, b = Pascoa; c = Natal; 0 = Nenhum)</td></tr>
        <tr><td>SCHOOLHOLIDAY</td><td>Feriado escolar</td></tr>
      </table> 
    </td>
  </tr>
</table>
<p>Tabela das Lojas - Descriçãqo das Variáveis</p>
<table>
  <tr>
    <td>
      <table>
        <tr><td>STORYTYPE</td><td>Tipo de Loja (a, b, c, d)</td></tr>
        <tr><td>ASSORTMENT</td><td>a = basic; b = extra; c = extend)</td></tr>
        <tr><td>COMPETIONDISTANCE</td><td>Distância do concorrente mais proximo</td></tr>
        <tr><td>COMPETIOTIONOPENSINCE (Month/Year)</td><td>Data que a loja concorrente foi aberta</td></tr>
        <tr><td>PROMO2</td><td>Promoção contínua e consecutiva em algumas lojas (0 = Não participa, 1 = Está participando)</td></tr>
        <tr><td>PROMO2SINCE (Yaer/Week)</td><td>Data que a loja começou a participar da PROMO2</td></tr>
        <tr><td>PROMOINTERVAL</td><td>Intervalos consecutivos que a PROMO2 é iniciada</td></tr>
      </table> 
    </td>
  </tr>
</table>
