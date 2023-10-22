# Transformação de dados do desafio

O primeiro passo para a transformação é a verificação dos cabeçalhos e dos tipos de dados de cada coluna para todas as tabelas.

Em seguida, remover colunas desnecessárias.

Posteriormente, foi separado os endereços dos employees de modo que número, rua, cidade e estado estejam separados usando delimitador de colunas e corrigindo casos individuais. 

Também foi preenchido valores nulos baseados no contexto em que estavam inseridos.

Aplicou-se um concatenar para local e nome do departamento afim de criar uma chave única para os departamentos.

Também foi criada uma nova tabela mesclada com trabalhadores e seus respectivos departamentos e gerentes de departamento, além dos nomes dos gerentes de cada um deles.

Por fim, as colunas de nome foram concatenadas de forma a obter uma informação mais completa.
