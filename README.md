# Sales Record System

Este projeto é uma aplicação Spring Boot para registrar e gerenciar vendas. Ele permite registrar vendas durante o dia, com o valor, metodo de pagamento e a descrição fornecidos pelo usuário. A data e a hora são registradas automaticamente.

## Funcionalidades

- **Registrar Vendas**: Adiciona uma nova venda com valor e descrição.
- **Data e Hora Automáticas**: A data e a hora são preenchidas automaticamente com a data e hora atuais.
- **Validações**: Validações são aplicadas ao valor e à descrição da venda.
- **Tratamento de Erros**: Mensagens de erro detalhadas são retornadas em caso de falhas.

## Tecnologias

- **Spring Boot**: Framework para desenvolvimento do backend.
- **PostgreSQL**: Banco de dados utilizado para armazenar os registros de vendas.
- **Flyway**: Gerenciador de migrações de banco de dados.

## Requisitos

- Java 17 ou superior
- PostgreSQL
- Gradle (para gerenciamento de dependências e construção do projeto)

## Configuração

1. **Clone o repositório**

   ```bash
   git clone https://github.com/CristianoMends/sales-record-system.git
   cd sales-record-system
