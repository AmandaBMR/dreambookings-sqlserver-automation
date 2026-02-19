# dreambookings-sqlserver-automation
# DREAMBOOKINGS — Base de Dados (SQL Server) + Automatização (Python)

## Objetivo
Implementar uma BD relacional para um sistema de aluguer de habitações, com automação e regras de negócio.

## Stack
SQL Server · T-SQL · Stored Procedures · Triggers · Python (pyodbc, Faker)

## Principais componentes
- Tabelas e relações (integridade referencial)
- Filegroups e organização por schemas/roles
- Povoamento automatizado com dados realistas (Python + Faker)
- Notificações por e-mail (Database Mail) via stored procedures

## Como correr
1) Criar BD e tabelas (scripts em /sql)
2) Configurar connection string
3) Executar scripts Python em /python para povoamento
