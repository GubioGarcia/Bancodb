# Banco de Dados do Banco

Este repositório contém um banco de dados SQL para uma instituição bancária fictícia. O banco de dados foi projetado com tabelas para armazenar informações sobre clientes, funcionários, agências, contas, negócios e empréstimos.

## Descrição do Banco de Dados

### Tabelas

O banco de dados consiste nas seguintes tabelas:

- `agencia`: Armazena informações sobre as agências bancárias, incluindo nome, número e cidade.
- `cliente`: Armazena informações sobre os clientes do banco, incluindo nome, data de nascimento, CPF, cidade, agência à qual estão vinculados e empréstimo associado.
- `funcionarios`: Contém informações sobre os funcionários do banco, como nome, CPF, matrícula, cidade e agência à qual estão vinculados.
- `conta`: Registra informações sobre as contas bancárias dos clientes, incluindo número, saldo, tipo de conta, agência e cliente associado.
- `negocios`: Mantém informações sobre transações de negócios, como tipo, data de início, data de término e agência associada.
- `emprestimo`: Armazena informações sobre empréstimos, incluindo número, data de empréstimo e valor.

### Funcionalidades

O banco de dados permite a realização das seguintes operações:

1. Cadastrar clientes e funcionários.
2. Realizar consultas para buscar informações, como nomes de clientes com contas no banco, suas cidades de residência e as cidades das agências onde têm contas.
3. Buscar clientes que têm contas na mesma cidade em que moram.
4. Encontrar clientes que têm contas em Aparecida de Goiânia e moram em Goiânia.
5. Buscar os três primeiros nomes de clientes com contas em Aparecida.
6. Obter informações sobre funcionários, agências e clientes em um único resultado.
7. Criar uma visão que exiba o nome dos funcionários, o nome da agência e o nome dos clientes, onde todas as pessoas estejam localizadas em Goiânia.
