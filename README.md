# Python_Pandas

O código realiza as seguintes operações:

1. Importa a base de dados `aluguel.csv` utilizando a função `read_csv` do Pandas com o separador `;`.
2. Verifica o tipo de dado da variável `dados`.
3. Exibe informações gerais sobre a base de dados, como o tipo de dados de cada coluna e as primeiras linhas da base.
4. Cria um DataFrame com a tipagem das variáveis.
5. Exibe o formato da base de dados, ou seja, o número de registros e colunas, e imprime uma mensagem com essas informações.
6. Organizando os dados em um DataFrame `.drop_duplicates()`.
7. Reindexação `range(nome_var_DataFrame.shape[0])`.

Além  disso, adicionei um arquivo "extra" na qual contém arquivos e comandos que capturam as informações desses arquivos sendo eles csv, json, txt, xslx ou em html:

1. Importa dados de um arquivo CSV - `pd.read_csv()`, verifica o tipo de dados, exibe informações gerais e a tipagem das variáveis.
2. Importa dados de arquivos JSON - `open()` e `pd.read_json()`.
3. Importa dados de arquivos de texto - `open()` e `pd.read_table()`.
4. Importa dados de arquivos Excel - `pd.read_excel()`.
5. Importa dados de arquivos HTML - `pd.read_html()`.





