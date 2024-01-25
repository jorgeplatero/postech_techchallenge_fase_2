# Modelo Preditivo de Série Temporal do Fechamento IBOVESPA

## Descrição do Projeto

O IBOVESPA é o índice de referência do mercado acionário brasileiro, criado em 1968, que mede o retorno total das carteiras teóricas compostas pelas ações mais negociadas na B3. Seu cálculo é baseado no peso das ações na carteira teórica e no valor de suas cotações do dia.
Para calcular o índice, multiplica-se o peso de cada ação pela sua cotação, resultando no número de pontos do Ibovespa. Devido à constante variação dos preços das ações conforme a oferta e demanda, o cálculo do índice é atualizado minuto a minuto, refletindo suas oscilações.

A Bolsa de Valores brasileira (B3) calcula e divulga o valor do IBOVESPA em tempo real durante o horário de negociação das 9h às 17h. Após o fechamento do mercado, o processo de encerramento ocorre. Às 17h, é liberado o valor preliminar de fechamento, considerando os últimos preços negociados. Entre 17h01 e 17h30, negociações continuam no after market, o que pode impactar esse valor.
O fechamento definitivo ocorre por volta das 18h após o leilão de encerramento, onde ocorrem as últimas negociações do dia. Esse leilão determina os preços de fechamento das ações, permitindo calcular o valor oficial de fechamento.
Posteriormente ao fechamento do mercado, a Bolsa realiza ajustes decorrentes de operações pós-mercado. Por volta das 19h30, é divulgado o valor final de fechamento do índice, que serve como referência para avaliar o desempenho diário do mercado acionário.

Este projeto tem por obtivo o desenvolvimento de um modelo preditivo capaz de prever o fechamento da bolsa, apresentando:

- Modelo com storytelling, desde a captura do dado até a entrega do modelo;
- Justificativa da técnica utilizada;
- Acurácia adequada (acima de 70%).

## Tecnologias Utilizadas

Python

## Fonte de Dados

Série IBOVESPA: https://br.investing.com/indices/bovespa-historical-data

## Colaboradores 

https://github.com/mateus-albuquerque

https://github.com/adriellytsilva
