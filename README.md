# Analise dos precos da gasolina no Brasil
Aprenda pandas respondendo 13 exercicios analisando o preço da gasolina no Brasil 

1° Exercício: Carregue os conjuntos de dados "gasolina_2000+.csv" e "gasolina_2010+.csv" em dois DataFrames diferentes e combine-os em um único DataFrame.

2° Exercício: Investigue as colunas e entenda o conjunto de dados usando o head() e info()

3° Exercício: Selecione a terceira entrada da coluna DATA INICIAL e verifique seu tipo.

4° Exercício: Você deve ter percebido que as colunas DATA INICIAL e DATA FINAL estão formatadas como string. Utilizando o método pd.to_datetime(), converta ambas colunas para Timestamp / Datetime.

5° Exercício: Crie uma nova coluna para representar o ano e o mês(aaaa-mm), utilizando a coluna DATA FINAL como referência.

6° Exercício: Utilizando o value_counts(), liste todos os tipos de produtos contidos na base de dados.

7° Exercício: Filtre o DataFrame para obter apenas dados da 'GASOLINA COMUM'. Grave em uma nova variável.

8° Exercício: Qual o preço médio de revenda da gasolina em agosto de 2008?

9° Exercício: Qual o preço médio de revenda da gasolina em maio de 2014 em São Paulo?

10° Exercício: Você conseguiria descobrir em qual(quais) estado(s) a gasolina ultrapassou a barreira dos R$ 5,00? E quando isso ocorreu?

11° Exercício: Qual a média de preço dos estados da região sul em 2012?

12° Exercício: Você conseguiria obter uma tabela contendo a variação percentual ano a ano para o estado do Rio de Janeiro?

13° Exercício/Desafio: Crie uma tabela contendo uma serie temporal com a diferença absoluta e percentual entre os valores mais baratos e caros. Apresente também ao lado os estados na qual os maiores e menores preços foram registrados.
