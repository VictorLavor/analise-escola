# analise-escola

# Análise de Dados das Escolas

Este projeto consiste em analisar informações sobre diversas escolas, incluindo o tipo, o número de alunos e o orçamento anual. O objetivo principal é fornecer insights sobre a distribuição dos orçamentos, comparando escolas públicas e particulares, e avaliar a relação entre o orçamento e o número de alunos em cada instituição.

## Descrição dos Dados

O dataset contém as seguintes colunas:

- **ID_Escola**: Identificador único para cada escola.
- **Nome_Escola**: Nome da escola.
- **Tipo_Escola**: Tipo da escola, podendo ser 'Publica' ou 'Particular'.
- **Numero_Alunos**: Número de alunos matriculados na escola.
- **Orcamento_Anual**: Orçamento anual da escola, em unidades monetárias.

## Informações do DataFrame

O conjunto de dados possui 15 entradas e 5 colunas, com os seguintes tipos de dados:

- 3 colunas de tipo `int64` (ID_Escola, Numero_Alunos, Orcamento_Anual).
- 2 colunas de tipo `object` (Nome_Escola, Tipo_Escola).

## Análises Realizadas

### 1. Orçamento Total

O orçamento total de todas as escolas somados é de **24.649.428** unidades monetárias.

### 2. Cálculo de Orçamento por Aluno

Foi calculado o orçamento por aluno para cada escola. As escolas com os maiores e menores orçamentos por aluno foram identificadas:

- **Maior Orçamento por Aluno**: Escola A com 655 unidades monetárias por aluno.
- **Menor Orçamento por Aluno**: Escola F com 578 unidades monetárias por aluno.

### 3. Média de Alunos por Tipo de Escola

A média de alunos nas escolas foi calculada separando por tipo de escola:

- **Escolas Particulares**: Média de **1.524** alunos.
- **Escolas Públicas**: Média de **3.854** alunos.

### 4. Quantidade de Escolas com Orçamento Acima de 1,5 Milhão

O número de escolas com um orçamento superior a **1.500.000** foi identificado, resultando em **7 escolas** com orçamentos acima deste valor.

## Conclusões

- As **escolas públicas** tendem a ter mais alunos em média do que as **escolas particulares**.
- A **Escola A** tem o maior orçamento por aluno, o que pode indicar um orçamento maior ou uma menor quantidade de alunos.
- A maior parte das escolas com orçamentos elevados estão em torno de 1,5 milhão, com **7 escolas** superando esse valor.

Este dataset fornece uma visão interessante sobre a distribuição de recursos entre escolas públicas e particulares, destacando diferenças significativas no orçamento por aluno e no número de alunos por tipo de escola.

## Tecnologias Utilizadas

- **Pandas**: Para manipulação e análise dos dados.
