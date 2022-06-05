# Challenge Navi Capital

Fizemos uma análise de dados das empresas de geração distribuída e geração centralizada efetiva, a fim de verificar a evolução da capacidade. 
Após os estudos resolvemos realizar a elaboração de um site com o intuíto de elencar as melhores empresas e atribuir um rating para verificar o nível de solvência.

O propósito do projeto é com o python automatizar a coleta de dados por meio de web scraping e, a partir do tratamento realizado em python, colocar os dados em uma base de dados MongoDB para que o backend possa puxar e colocar no site. 
No site a ideia é verificar qual é o segmento com maior capacidade instalada e assim poder elencar dentro desse segmento qual a empresa que mais investiu. 

Após elencar a empresa, nós atribuiremos um rating próprio levando em conta os seguintes indicadores:

indicadores: 

  lucro oper. /receita total(%);
  roic(%);
  ebit / despesa de juros(x);
  ebitda / despesas de juros(x);
  fluxo de caixa livre / divida total(%);
  fluxo de caixa operacional / divida total(%);
  divida total / ebitda(%);
  divida total / divida total + patrimonio(%);

A ideia é utilizar a base pública da CVM para, com o python, realizar o tratamento e verificar os indicadores acima.
Após a atribuição do rating, os investidores poderão ver o nível de solvễncia da empresa e verificar a disponibilidade de crédito para elas.
