# Projeto de Modelagem Dimensional para Análise de Dados dos Professores
## Descrição
Este projeto tem como objetivo criar um esquema em estrela, conhecido como star schema, a partir de um diagrama relacional fornecido. O foco da modelagem será a análise dos dados relacionados aos professores.

## Objetivo
O objetivo principal é construir um modelo dimensional que permita a análise multidimensional dos dados dos professores, cursos ministrados e departamentos.

## Tabela Fato
A tabela fato será responsável por armazenar o contexto analisado, refletindo diversos dados sobre os professores, cursos ministrados e os departamentos aos quais estão associados.

## Tabelas Dimensão
Além da tabela fato, serão criadas tabelas dimensão que conterão detalhes relacionados ao contexto. Essas tabelas incluirão informações detalhadas sobre os professores, cursos e departamentos, permitindo uma análise mais granular e detalhada.

## Tabela Dimensão de Datas
Para suportar análises temporais, será adicionada uma tabela dimensão de datas. Como os dados de datas não estão disponíveis no modelo relacional fornecido, será necessário supor essas informações e criar os campos necessários para modelagem. Diferentes formatos e granularidades de datas podem ser utilizados para atender às necessidades analíticas do projeto.
