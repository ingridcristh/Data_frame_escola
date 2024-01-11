# Data Frame Escola

## Descrição do Projeto

O projeto `Data Frame Escola` visa criar e manipular um conjunto de dados representando uma escola fictícia. Este conjunto de dados é composto por informações sobre alunos, cursos de programação e suas respectivas matrículas.

## Seções

### 1. Creando Nombre

Nesta seção, são gerados os nomes dos alunos utilizando dados dos nomes mais comuns fornecidos pelo IBGE(https://servicodados.ibge.gov.br/api/v1/censos/nomes).

### 2. Incluyendo Id de Alumnos

Cada aluno recebe um ID único nesta etapa, permitindo uma identificação fácil e rastreamento dos registros.

### 3. Creando Cursos

Aqui, são criados diversos cursos de programação, extraídos da url(https://www.tiobe.com/tiobe-index/)

### 4. Adicionando Index

É criado um índice para cada curso, facilitando a referência e manipulação posterior dos dados.

### 5. Borrando Columnas

Colunas desnecessárias são removidas, resultando em um conjunto de dados contendo apenas as colunas de ID e nombre_cursos.

### 6. Matriculando Alumnos

Os alunos são matriculados nos cursos disponíveis, e é calculada a quantidade de cursos que cada aluno está realizando.

### 7. Seleccionando Alumnos

Nesta seção, os alunos são selecionados para participar de cursos específicos de maneira aleatória utilizando o metodo random()

### 8. Salida en Diferentes Formatos

Possibilidade de extrair os dados em diferentes formatos, como HTML, XLSX e JSON, para aumentar a flexibilidade no uso dos dados.

### 9. Creando Banco de Dados

É criado um banco de dados interno usando o parâmetro `engine`, permitindo a persistência e consulta eficientes dos dados.

### 10. Buscando en el Banco de Dados

Demonstração de como realizar buscas no banco de dados interno, proporcionando uma análise eficiente dos dados armazenados.

### 11. Nombres para el Ingreso

Listagem dos alunos matriculados em um determinado curso, com a possibilidade de impressão dessas informações. As matrículas são provenientes de vários cursos de computação, extraídas de outro site.

## Tecnologia y Frameworks 

- Python
- Sqlite
- Pandas
- Numpy

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas, tiver sugestões ou melhorias, sinta-se à vontade para criar issues ou pull requests.
