# Banco-de-dados-Projeto-individual

=> Existem outras entidades além dessas três (alunos , turmas , cursos) ?

Existem outras entidades que podem fazer parte do banco de dados,facilitando a dsitruibuição e visualição dos dados.
O banco de dados pode conter tabelas para funcionários, disciplinas, boletins , lista de presença e etc...
E ainda incluir entidades que sirvam de junção para a relação entre entidades.

=> Quais são os principais campos e tipos ?

O banco de dados proposto possui o campos de tipos comuns como varchar, char, e int, assim como, campos do tipo timestamp e DATE.
O campos principais são ID, nome (primeriro_nome e ultimo_nome), matricula, nome do curso e numero da turma.

=> Como essas entidades estão relacionadas ?

Foram utilizadas relações 1:n , n:1 e n:m.
Segue a lista de relação entre entidades: 
cursos 1:n turmas
turmas n:m funcionarios
turmas n:m alunos
funcionarios n:m turmas
funcionarios n:m disciplinas
disciplinas n:m funcionarios .

=========================================================

