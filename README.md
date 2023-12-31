﻿# API de cadastro e login de usuários.

Permite o gerenciamento de criação e login de usuários, retornando um TOKEN `JWT` para autenticação. A Api foi desenvolvida utilizando `Node.js`, `Express`, `Prisma ORM` e `MongoDB`.

## Instalação e Execução

Para executar esta API em sua máquina local, siga os seguintes passos:

1. Certifique-se de ter o Node.js e o MongoDB instalados em sua máquina.

2. Faça o clone deste repositório e acesse o diretório raiz.

3. Instale as dependências necessárias executando o seguinte comando no terminal:

```
npm install
```

Crie um arquivo .env na raiz do projeto e defina as seguintes variáveis de ambiente:

```PORT=3000
DATABASE_URL=<sua_url_de_conexão_mongodb>
```

Inicie o servidor através do script executando o comando:

```
npm start
``` 

O servidor estará rodando na porta especificada no arquivo `.env`

## Documentação da API

A documentação da API está disponível no seguinte endereço:
URL: /docapi
Método: GET

## Resumo do Projeto

A "API de Login de Usuários" é um projeto que demonstro minhas habilidades no desenvolvimento de servidores e serviços utilizando tecnologias como Node.js, Express, Prisma ORM e MongoDB. O objetivo deste projeto é fornecer um sistema simples de gerenciamento de usuários, permitindo a criação, leitura, atualização e exclusão de registros de usuários.

## Tecnologias Utilizadas

### Node.js

É uma plataforma de código aberto que permite a execução de código JavaScript do lado do servidor. Utilizo o Node.js para criar o servidor da aplicação e gerenciar as requisições HTTP.

### Express

É um framework web para Node.js que simplifica a criação de aplicativos e APIs. Utilizo o Express para criar as rotas e endpoints da API.

### Prisma ORM

É uma ferramenta de mapeamento objeto-relacional (ORM) que facilita o acesso e a manipulação do banco de dados. Utilizo o Prisma ORM para interagir com o MongoDB e realizar operações no banco de dados de forma mais eficiente.

### MongoDB

É um banco de dados NoSQL orientado a documentos, que armazena os dados em formato JSON-like. Utilizo o MongoDB para persistir os dados dos usuários, permitindo uma integração rápida e flexível com a API.

### Swagger

É uma ferramenta que permite a criação de documentação interativa para APIs. Utilizo o Swagger para fornecer uma documentação clara e acessível aos desenvolvedores, descrevendo os endpoints disponíveis, seus parâmetros e respostas esperadas.

## Funcionalidades da API:

1. Realizar login de usuário, obtendo um TOKEN JWT de autenticação.
2. Obter a lista de todos os usuários cadastrados.
3. Criar um novo usuário, fornecendo email e senha.
4. Obter informações de um usuário específico, buscando pelo seu ID.
5. Atualizar os dados de um usuário existente.
6. Deletar um usuário do sistema.

## Importância do Projeto

Fundamental para demonstrar minha capacidade de criar e gerenciar um servidor funcional, com integração ao banco de dados para armazenamento de informações. Além disso, ao utilizar tecnologias como o Prisma ORM e o MongoDB, mostro habilidades em lidar com diferentes tipos de bancos de dados, inclusive NoSQL.

A utilização do Swagger para a documentação da API é de extrema importância, pois facilita a compreensão e o uso da API por outros desenvolvedores. A documentação clara e acessível é essencial para que outros possam consumir e interagir facilmente com os recursos oferecidos pela API.

É um projeto inicial, com um escopo relativamente simples e focado em funcionalidades básicas de gerenciamento de usuários.
Atualmente, estou trabalhando em projetos mais desafiadores e de maior escala, onde aplico conceitos avançados de arquitetura e melhores práticas de desenvolvimento. Paralelamente a esses projetos profissionais, continuo aprimorando e implementando novas funcionalidades nos meus projetos pessoais como forma de estudo e aprendizado contínuo.
