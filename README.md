# staking-crypto-report
Relatório de contratos de staking disponíveis e suas respectivos rendimentos em APR/APY.

O StakingReport é um projeto criado para enfrentar o desafio de coletar dados de staking de três plataformas diferentes: CoinmarketCap, PancakeSwap e Binance Staking. Além disso, ele permite gerar relatórios diários, semanais e mensais com esses dados.

Para a plataforma CoinmarketCap, foram adotadas as seguintes estratégias:

Inspeção da página para identificar os elementos relevantes, como cabeçalho, linhas, colunas e imagens.
Criação de um loop para percorrer as linhas e indicar quais elementos devem ser coletados.
Na segunda tentativa, incluiu-se a coleta das imagens.
Exportação dos dados para um dataframe e também para um arquivo Excel, facilitando a análise visual da estrutura dos dados.
Na terceira tentativa, a abordagem adotada foi criar toda a estrutura da tabela, linha por linha e coluna por coluna.

Ao final do processo, o StakingReport envia o conteúdo da tabela no corpo do e-mail, proporcionando uma forma prática de compartilhar os dados coletados.

Este projeto visa facilitar o acompanhamento e análise dos dados de staking, fornecendo uma solução eficiente para a coleta e organização dessas informações.
