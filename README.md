SQL (Structured Query Language) é a linguagem padrão para interagir com bancos de dados relacionais. Usamos SQL para consultar, inserir, atualizar e deletar dados.

1. SELECT
Comando usado para buscar dados em uma tabela.
Exemplo: SELECT name FROM world; — retorna a coluna name da tabela world.

2. WHERE
Usado para filtrar linhas com base em uma condição.

Exemplo: SELECT * FROM world WHERE continent = 'Europe'; — retorna somente países da Europa.

3. AND, OR
Operadores lógicos para combinar condições.
Exemplo: WHERE population > 1000000 AND continent = 'Asia'

4. ORDER BY
Ordena o resultado por uma ou mais colunas.
Exemplo: ORDER BY population DESC — maior população primeiro.

5. LIMIT
Restringe o número de linhas retornadas.
Exemplo: LIMIT 10 — retorna as 10 primeiras linhas.

6. COUNT, SUM, AVG, MAX, MIN
Funções agregadas para contar, somar, tirar média, achar máximo e mínimo de colunas.
Exemplo: SELECT COUNT(*) FROM world; — número total de linhas.

7. GROUP BY
Agrupa linhas que tenham o mesmo valor em uma ou mais colunas para aplicar funções agregadas.
Exemplo: SELECT continent, COUNT(*) FROM world GROUP BY continent;

8. JOIN
Une dados de duas ou mais tabelas com base em uma coluna comum.
Exemplo: SELECT * FROM game JOIN goal ON game.id = goal.matchid;

9. DISTINCT
Elimina linhas duplicadas no resultado.

10. Subqueries
Uma consulta dentro de outra.


Refere-se
A consulta de bancos de dados relacionais com eficiência, desde operações simples até consultas mais avançadas envolvendo junções, agrupamentos e subconsultas.
