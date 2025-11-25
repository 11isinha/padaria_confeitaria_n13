# Petrova Bakery - API RESTful🥐
## Objetivo

- Criar uma API RESTful completa do zero utilizando Node.js e Express para a Petrova Bakery.

## Requisitos do Projeto📝

- Inicialização do projeto com npm init

- Configuração do servidor Express

- Implementação das operações CRUD (Create, Read, Update, Delete)

- Organização de pastas

# Passos para Implementação💻
## Passo 01 e 02

Criar uma pasta na área de trabalho.

Colocar um nome adequado, por exemplo: padaria_confeitaria.

Abrir a pasta no Visual Studio Code.

## Passo 03

Neste momento, crie o arquivo server.js que será fundamental para o back-end da aplicação. Nele estarão as operações CRUD (Create, Read, Update, Delete), conforme descrito abaixo:

- GET /produtos — Lista todos os produtos

- GET /produtos/:id — Busca um produto específico

- POST /produtos — Cria um novo produto

- PUT /produtos/:id — Atualiza um produto

- DELETE /produtos/:id — Deleta um produto

No código do server.js, importe os módulos necessários, configure a porta (3000), adicione o middleware, inicie o Supabase e crie a rota teste. Em seguida, implemente as operações CRUD.

## Passo 04

No terminal, inicie o projeto com o comando:

npm init -y

## Passo 05

Crie o banco de dados no Supabase:

Acesse o site do Supabase e crie um novo projeto.

No canto esquerdo, clique em SQL Editor.

Para criar a tabela, siga o modelo indicado.

Use o Table editor para visualizar sua tabela.

## Passo 06

No Supabase, clique na casinha no canto esquerdo para acessar o painel de configuração.

Copie a URL e a API Key geradas para o seu projeto.

## Passo 07

Volte no Visual Studio Code e crie o arquivo .env.

No arquivo .env, cole a URL e a API Key copiadas, da seguinte forma:

- SUPABASE_URL=<sua_url>
- SUPABASE_KEY=<sua_api_key>
- PORT=3000

## Passo 08

No terminal, instale as dependências necessárias:

Instale o Express:

- npm install express


- Instale o CORS, dotenv e @supabase/supabase-js:

- npm install cors dotenv @supabase/supabase-js


Por fim, execute o servidor com o comando:

-node server.js


Se tudo estiver correto, o link do servidor local será exibido no terminal.

Testando as Rotas CRUD

Utilize a extensão Thunder Client no Visual Studio Code para testar as rotas da API.

Rotas:

- GET — Buscar todos os produtos:

http://localhost:3000/produtos


- GET — Buscar produto por ID:

http://localhost:3000/produtos/1


- POST — Criar novo produto:

http://localhost:3000/produtos


- PUT — Atualizar produto:

http://localhost:3000/produtos/1


- DELETE — Deletar produto:

http://localhost:3000/produtos/1


## Finalizado! Agora você tem uma API RESTful funcionando para a Petrova Bakery! �

https://www.canva.com/design/DAG5te40Ino/103FSTSiC6Gvuz58qpvi9w/edit?utm_content=DAG5te40Ino&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
## link canva 
