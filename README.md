# Tasks Automation
Automação de rotinas diárias utilizando o Python como ferramenta para o fomento da produtividade.

## 1 - Extração de dados externos e automação de tarefas
### Desafio
Todos os dias o nosso sistema atualiza as vendas do dia anterior. O seu trabalho diário, como analista, é enviar um e-mail para a diretoria, assim que começar a trabalhar, com o faturamento e a quantidade de produtos vendidos no dia anterior.
<br>***Como é possível automatizar estes processos repetitivos para aumentar a produtividade no escritório?***
- E-mail da diretoria: seugmail+diretoria@gmail.com
- Local onde o sistema disponibiliza as vendas do dia anterior: https://drive.google.com/drive/folders/1mhXZ3JPAnekXP_4vX7Z_sJj35VWqayaR?usp=sharing  

### Bibliotecas Utilizadas
- `pandas` -> Permite a interação com arquivos e planilhas
- `pyautogui` -> Automação do mouse e teclado
- `time` -> Controla o tempo de processamento do programa
- `pyperclip` -> Habilita as funções copiar/colar

## 2 - Limpeza e análise de base de dados
### Desafio
Você trabalha em uma empresa de telecom e tem clientes de vários serviços diferentes, entre os principais: internet e telefone.
O problema é que, analisando o histórico dos clientes dos últimos anos, você percebeu que a empresa está com Churn de mais de 26% dos clientes.
Isso representa uma perda de milhões para a empresa. ***O que a empresa precisa fazer para resolver isso?***

### Bibliotecas Utilizadas
- `pandas` -> Permite a interação com arquivos e planilhas
- `plotly.express` -> Criação de gráficos a partir de base de dados
<h4><p align="center">Gênero x Churn</p></h4>
<p align="center">
  <img src="img/2/genero-vs-churn.PNG" width="65%">
</p>

<h4><p align="center">Meses como Cliente x Churn</p></h4>
<p align="center"><img src="img/2/meses-vs-churn.PNG" width="65%"></p>

<h4><p align="center">Valor Mensal x Churn</p></h4>
<p align="center"><img src="img/2/valormes-vs-churn.PNG" width="65%"></p>

<h4><p align="center">Total Gasto x Churn</p></h4>
<p align="center"><img src="img/2/total-gast-vs-churn.PNG" width="65%"></p>

## 3 - Análise de Dados e Previsão de Vendas
### Desafio
Prever as vendas que vamos ter em determinado período com base nos gastos em anúncios nas 3 grandes redes que a empresa Hashtag investe: TV, Jornal e Rádio.
***Qual a importância de cada variável para as vendas?
A empresa está investindo de maneira correta?***

### Bibliotecas Utilizadas
- `pandas` 
- `seaborn`
- `matplotlib.pyplot`
- `sklearn.model_selection > train_test_split`
- `sklearn.linear_model > LinearRegression`
- `sklearn.ensemble > RandomForestRegressor`
- `sklearn > metrics`

<h4><p align="center">Criação de tabela a partir de base de dados</p></h4>
<p align="center"><img src="img/3/tabela-vendas.PNG" width="25%"></p>

<h4><p align="center">Gráfico de Vendas</p></h4>
<p align="center"><img src="img/3/grafico-vendas.PNG" width="50%"></p>

<h4><p align="center">Análise Estatística do Coeficiente de Precisão</p></h4>
<p align="center"><img src="img/3/analise-precisao-vendas.PNG" width="30%"></p>

<h4><p align="center">Gráfico de Previsão das Vendas</p></h4>
<p align="center"><img src="img/3/previsao-vendas.PNG" width="35%"></p>

## 4 - Extração de dados da WEB e conversão de moedas
### Desafio
Trabalhamos em uma importadora e o preço dos nossos produtos é vinculado a cotação de:
- Dólar
- Euro
- Ouro  
<br>Precisamos buscar através da WEB, de forma automática, a cotação desses 3 itens e saber quanto devemos cobrar pelos nossos produtos, considerando uma margem de contribuição que temos na nossa base de dados.  
***Como é possível automatizar estes processos utilizando a WEB como ferramenta de busca e obter uma atualização automática das cotações?***

- Base de Dados: https://drive.google.com/drive/folders/1QHOQt1J7d5Z4sBFKL9GN699OcPh2aVaP?usp=sharing

### Bibliotecas Utilizadas
- `selenium > webdriver`
- `selenium.webdriver.common.keys > Keys`

<h4><p align="center">Tabela criada após a extração e tratamento de dados</p></h4>
<p align="center"><img src="img/4/tabela-tratada.PNG" width="70%"></p>
