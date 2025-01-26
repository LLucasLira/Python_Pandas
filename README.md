# Python_Pandas

<h3>Arquivo: Base de dados</h3>
O código realiza as seguintes operações:

1. Importa a base de dados `aluguel.csv` utilizando a função `read_csv` do Pandas com o separador `;`.
2. Verifica o tipo de dado da variável `dados`.
3. Exibe informações gerais sobre a base de dados, como o tipo de dados de cada coluna e as primeiras linhas da base.
4. Cria um DataFrame com a tipagem das variáveis.
5. Exibe o formato da base de dados, ou seja, o número de registros e colunas, e imprime uma mensagem com essas informações.
6. Organizando os dados em um DataFrame `.drop_duplicates()`.
7. Reindexação `range(nome_var_DataFrame.shape[0])`.

<h3>Arquivo: Imóveis Residenciais</h3>

1. Importação da base de dados
2. Identificação de tipos de imóveis únicos `drop_duplicates()`
3. Método `.isin()` para identificar se o valor da coluna Tipo corresponde a algum desses tipos residenciais.
4. Exportação da base filtrada:

<h3>Arquivo: Extra 1</h3>
Comandos que capturam as informações de arquivos csv, json, txt, xslx ou em html:

1. Importa dados de um arquivo CSV - `pd.read_csv()`, verifica o tipo de dados, exibe informações gerais e a tipagem das variáveis.
2. Importa dados de arquivos JSON - `open()` e `pd.read_json()`.
3. Importa dados de arquivos de texto - `open()` e `pd.read_table()`.
4. Importa dados de arquivos Excel - `pd.read_excel()`.
5. Importa dados de arquivos HTML - `pd.read_html()`.

<h3>Arquivo: Extra 2</h3>
Operações básicas utilizando a biblioteca pandas do Python para criar e manipular objetos do tipo Series e DataFrame

1. Criação/ Modificação de uma Series com uma lista de dados.
2. Criação/ Modificação de um DataFrame a partir de uma lista.

<h3>Exercícios -  Seleção e Frequência:</h3>

1. Selecione somente os imóveis classificados com tipo "Apartamento";
2. Selecione os imóveis classificados com tipo "Casa", "Casa de Condomínio" e "Casa de Vila";
3. Selecione os imóveis com área entre 60 e 100 metros quadrados, incluindo os limites;
4. Selecione os imóveis que tenham pelo menos 4 quartos e aluguel menor que R$ 2.000,00.


