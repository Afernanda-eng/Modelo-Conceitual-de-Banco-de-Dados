# Modelo-Conceitual-de-Banco-de-Dados

Este repositório contém o modelo conceitual de banco de dados para um sistema de gerenciamento de tarefas e projetos.

## Entidades Principais
- *Trabalhador*: Nome, Sexo, Data de Nascimento, CPF, Endereço, Remuneração.
- *Departamento*: Nome, Número Identificador, Localização.
- *Projeto*: Nome, Número Identificador, Localização.
- *Dependente*: Nome, Sexo, Data de Nascimento, Parentesco.

## Relacionamentos
- *Trabalha para*: Um trabalhador trabalha em um departamento.
- *Gerencia*: Um trabalhador (opcional) gerencia um departamento, a partir de uma data de início.
- *Trabalha em*: Um trabalhador participa de vários projetos e um projeto possui vários trabalhadores.
- *Supervisiona*: Um trabalhador (gerente) pode supervisionar outros trabalhadores.
- *Depende de*: Um trabalhador pode ter dependentes.

## Instruções
- O diagrama foi criado na ferramenta Lucidchart.
- Para mais detalhes, consulte as entidades e os relacionamentos descritos acima.
