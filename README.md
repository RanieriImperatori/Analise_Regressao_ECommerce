# Analise_Regressao_ECommerce

Uma empresa de e-commerce, comercializa produtos através de seu website e através do seu app para dispositivos móveis.  
  
Para efetuar uma compra, um cliente realiza um cadastro no portal (usando web site ou app). Cada vez que o cliente realiza o login, o sistema registra o tempo que fica logado, seja no app ou no web site. Para cada cliente, a empresa mantém o registro de vendas com o total de gasto por mês.  
  
A empresa gostaria de aumentar as vendas, mas o orçamento permite investir somente no web site ou no app, neste momento. O objetivo é melhorar a experiência do cliente durante a navegação no sistema, aumentando o tempo logado, aumentando o engajamento e, conseguentemente, aumentando as vendas.  
  
O meu papel neste trabalho como Cientista de Dados, é auxiliar a empresa a tomar essa decisão com base em dados. Vamos utilizar a construção de um modelo de Regressão Linear, para entender como as variáveis se relacionam entre si. Com base no melhor entendimento das relações entre as variáveis, será possível indicar para a empresa, qual a melhor maneira de investir (web site ou app) para atingir o aumento nas vendas desejado. Importante destacar, que a escolha da utilização de modelos de Regressão se justfica pelo fato de ser um algoritmo simples e que permite a leitura do relacionamento entre as variáveis de maneiro muito simples - diferente de outros algoritmos que também poderia ser utilizados nesta pesquisa.
  
*Os dados usados neste notebook são fictícios, mas que representam dados reais. Os dados representam um mês de operação do portal de e-commerce.*  
  
**Dicionário de dados:**
* tempo_cadastro_cliente (float64): tempo que o cliente está cadastrado. O número de meses foi convertido para o número de anos.  
* numero_medio_cliques_por_sessao (float64): número médio de cliques (ou toques) em cada sessão.  
* tempo_total_logado_app (float64): tempo total logado no app em minutos.  
* tempo_total_logado_website (float64): tempo total logado no web site em minutos.  
* valor_total_gasto (float64): valor total gasto pelo cliente em um mês em R$.
