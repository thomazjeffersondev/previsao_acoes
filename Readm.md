
1- Obtenção e Pré-processamento dos Dados:
- Utilizamos a biblioteca pandas para ler os dados do arquivo CSV e realizar o pré-processamento.

- Removemos as linhas com valores nulos ou missing.

- Convertimos as variáveis categóricas em variáveis numéricas utilizando a técnica de one-hot encoding.

- Normalizamos as variáveis numéricas utilizando a técnica de standard scaling.

- Você definiu uma lista de códigos de ações (lista_tickres) e os nomes das empresas associadas (tickers).

- A função carregar_dados recupera os dados históricos de ações para um determinado código dentro de um intervalo de datas especificado usando o yfinance. Ela retorna um DataFrame com colunas para data e preço de fechamento.

- A função prever_dados prepara os dados para a previsão usando o Prophet. Ela converte a coluna de data para o formato necessário e treina um modelo de previsão. O modelo, então, faz previsões para os preços futuros das ações.

2 - Aplicativo Streamlit:

- Criamos um aplicativo Streamlit que permite ao usuário selecionar uma ação e um intervalo de datas para visualizar os dados históric

- Você criou um aplicativo Streamlit com um menu na barra lateral.

- O menu permite ao usuário selecionar uma ação e um intervalo de datas para visualizar os dados históricos e fazer previsões

- Os usuários podem selecionar um código de ação, inserir datas de início e fim, e escolher o número de meses para a previsão.
- O aplicativo exibe um gráfico com os dados históricos e as previsões futuras.

Visualização:
- Os dados históricos são visualizados em um gráfico de linha.
- As previsões futuras são visualizadas em um gráfico de área.

