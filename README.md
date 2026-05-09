#  Projeto: Controle de estoque com ALV
#  Autor: Dylan Krausse
#  Descrição: Sistema de controle de estoque desenvolvido em ABAP, com cadastro de produtos, registro de entradas e saídas e consulta de dados em ALV.

# Controle de Estoque com Relatório ALV (ABAP)

Projeto desenvolvido em ABAP utilizando SAP GUI com intuito de treinar ABAP clássico com ALV.

## Funcionalidades
- Cadastro produtos
- Registro de entrada e saída de produtos
- Consulta de produtos em ALV
- Consulta de movimentos em ALV

## Tecnologias
- ABAP
- SAP GUI
- ALV (REUSE_ALV_GRID_DISPLAY)
- Open SQL

## Desafios 
- Relação entre estruturas, tabelas e tabelas internas
- Adaptar o Código para cada ação do programa (Cadastro, entrada, saída e consulta de produto e movimento) 
- Aprender os comando COMMIT WORK, ROLLBACK WORK e USING e aplicar-los com êxito 

## Como funciona

O relatório principal exibe um ALV com dados das tabelas ZTB_PRODUTO e ZTB_MOV_ESTOQUE.

Através de radiobuttons, o usuário pode escolher a ação que deseja:
- Cadastrar Produto
- Registrar Entrada
- Registrar Saída
- Consultar Produtos
- Consultar Movimento

