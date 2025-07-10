Este projeto simula o controle de empréstimos de uma biblioteca usando SQL.

Sistema simples de controle de biblioteca.
# Projeto SQL - Biblioteca 📚

Este projeto simula o controle de empréstimos de uma biblioteca usando SQL.

## 🚀 Tecnologias Utilizadas- SQL
- MySQL
  
## 🔍 Estrutura do Projeto
- 01-criacao-tabelas.sql → Criação das tabelas.
- 02-insercao-dados.sql → Inserção dos dados.
- 03-consultas-basicas.sql → Consultas simples.
- 04-joins.sql → Consultas com JOIN.
- 05-filtros-e-subconsultas.sql → Consultas com filtros e subconsultas.
- 06-group-by-e-ordenacao.sql → Agrupamentos e ordenações.
- 07-desafio-final.sql → Consulta final do desafio.

## ✍️ Descrição das Etapas

### Etapa 1: Criação das Tabelas- Tabelas criadas: `livros`, `usuarios`, `emprestimos`- Definidas chaves primárias e estrangeiras.

### 📂Etapa 2: Inserção dos Dados
- 4 livros adicionados.
- 3 usuários adicionados.
- 3 empréstimos registrados.

### 📂 Etapa 3: Consultas Básicas
Liste todos os usuários cadastrados.
Liste todos os livros da biblioteca.
Liste todos os empréstimos realizados (mostrar ID, livro_id, usuario_id, data_emprestimo).

### 📂 Etapa 4: Junção (JOIN)
Mostre o nome dos usuários, o título dos livros emprestados e a data de empréstimo.
Mostre todos os livros, mesmo os que nunca foram emprestados (use LEFT JOIN).
Mostre o nome de todos os usuários e as datas dos empréstimos que fizeram (se não fizeram, mostrar o nome e NULL para a data).
Dica: escolha a tabela base certa!
Liste todos os livros e, se tiverem sido emprestados, mostre o nome do usuário que pegou e a data do empréstimo.
Liste somente os usuários que fizeram empréstimos, com o título dos livros que pegaram e a data do empréstimo.
Liste todos os empréstimos feitos, mostrando o nome do usuário e o título do livro.
Liste todos os livros que nunca foram emprestados.

### 📂 Etapa 5: Filtros e Subconsultas
Liste apenas os empréstimos que ainda não foram devolvidos.
Mostre quais livros nunca foram emprestados.
Liste os usuários que já realizaram mais de 1 empréstimo.

### 📂 Etapa 6: Agrupamento (GROUP BY) e Ordenação
Mostre a quantidade de empréstimos feitos por cada usuário.
Mostre os livros emprestados, ordenados pela data de empréstimo mais recente.
Mostre os 2 livros mais antigos (menor ano de publicação).

### 📂 Etapa 7: Desafio Final 🔥
Monte uma consulta que mostre:
O nome do usuário
O nome do livro
A quantidade total de dias que o livro ficou emprestado (considerando a devolução ou, se ainda não devolvido, até a data de hoje usando CURRENT_DATE).
Criar o dashboard da consulta utilizando o Power BI


- 📚 O que Aprendi- Como criar múltiplas tabelas relacionais.
- Como utilizar INNER JOIN e LEFT JOIN.
- Como aplicar GROUP BY e filtros com WHERE.
- Criação de dashboard para visualização dos dados em Power Bi.
