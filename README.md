Leilões TDSat

-Sobre o projeto

O Leilões TDSat é um sistema informatizado desenvolvido para uma casa de leilões, com o objetivo de gerenciar os produtos disponíveis para venda em leilão. O sistema permite o cadastro, a consulta e o controle de status dos itens leiloados (por exemplo, se um produto está "À Venda" ou "Vendido"), além do registro do valor de cada item.

O projeto foi desenvolvido como parte das atividades práticas de versionamento de código, aplicando o Git e o GitHub como ferramentas de controle de versão e colaboração.

-Tecnologias utilizadas

- Java — linguagem de programação utilizada no desenvolvimento da aplicação
- MySQL / MariaDB — sistema de gerenciamento de banco de dados utilizado para armazenar as informações dos produtos leiloados
- Git e GitHub — controle de versão e hospedagem do repositório

-Estrutura do banco de dados

O banco de dados `uc11` contém a tabela `produtos`, com os campos:

| Campo  | Tipo   | Descrição                          |
|--------|--------|-------------------------------------|
| id     | bigint | Identificador único do produto      |
| nome   | text   | Nome do produto leiloado            |
| valor  | int    | Valor do produto                    |
| status | text   | Situação do produto (Vendido / A Venda) |

-Como executar o projeto

1. Importe o arquivo `uc11.sql` no seu SGBD (MySQL/MariaDB).
2. Configure a conexão com o banco de dados no projeto Java.
3. Execute a aplicação.
