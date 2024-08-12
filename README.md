# Machine-Learning-regrassao-analise-de-dados-penguins

ESTA PEQUENA ANALISE DE DADOS, BUSCA CRIAR UMA ANALISE PREDITIVA USANDO UMA MACHINE LEARNING DE REGRESSÃO PARA DESCOBRIR O PESO DE UM PENGUIM, ATRAVES DE SUAS CARACTERISTICAS, SIGA O PASSO A PASSO:

1. Análise exploratória

Atributos por sexo
Atributos por espécie:
Atributos por ilha:

2. Dados

2.1. Tratar Valores nulos

A base de dados possui valores faltantes.

2.2. Variáveis numéricas

Identificando as variáveis numéricas e criando uma nova coluna padronizando seus valores. A nova coluna tem o mesmo nome da coluna original acrescida de "_std".

2.3. Variáveis categóricas

Identificando as variáveis categóricas nominais e ordinais, e criando uma nova coluna aplicando a

técnica correta de conversão a seus valores. A nova coluna tem o mesmo nome da

coluna original acrescidade de "_nom" ou "_ord".

2.4. Limpeza

Descarte das colunas originais e mantendo apenas a variável resposta e as variáveis

preditivas com o sufixo _std", _nom" e "_ord".

2.5. Treino/Teste

Separando a base de dados em treino e teste utilizando uma proporção de 2/3 para treino e 1/3

para testes.

3. Modelagem

3.1. Treino

Treinar o modelo de regressão linear com os dados de treino (2/3).

3.2. Avaliação

Calcular o RMSE para o modelo de regressão linear treinado com os dados de teste (1/3).

4. Predição
