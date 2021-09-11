# API Personagens Marvel - Node.js

<img src="https://s2.glbimg.com/9pQc-JNMBAbrGsiw0408v8Iy6tQ=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/c/A/F3vxowTmKcB8RdDcKAzA/marvel-future-revolution.jpg" alt="Marvel Logo" style="zoom:33%;" />

> API criada para estudar conceitos de back-end, utilizando a linguagem de programação JavaScript e o banco de dados MongoDB. Nessa API eu crio um CRUD completo de personagens da MARVEL.

Para utilizar o projeto faça o dowload do arquivo zip, ou faça o clone em seu computador utilizando o Git. Execute o comando `npm i` dentro da pasta do projeto em seu computador(a pasta que contém o arquivo package.json), para baixar as dependencias do projeto.

## Executando o projeto

_Essa API utiliza o mongodb como banco de dados e o mongoose como ODM, então antes de testar a API certifique se você possui o MongoDb instalado em seu computador(https://www.mongodb.com/try/download/community)._

Além disso, você precisa criar o arquivo .env com a url do seu banco, _utilize o arquivo .env.exemple para criar o seu_. Esse é um exemplo de string de conexão com o banco de dados: mongodb://localhost:27017/db_marvel.

Agora você pode executar o projeto:

- Para executar o projeto com o nodemon, digite no terminal:

```bash
npm run dev
```

- Para executar o projeto com o node, digite no terminal:

```bash
npm start
```

## Testando a API

Você pode utilizar as ferramentas:

- Postman
- Insomnia
- Thunder Client (plugin no vsCode)

Exemplos de URLs:

- Essa é a URL de teste padrão: http://localhost:3000/personagens
- Para buscar por ID, Editar ou Apagar, insira o ID na URL: http://localhost:3000/personagens/5
- Para fazer uma busca com query string, esse é um exemplo de URL: http://localhost:3000/personagens/filter?identidade=Spider-Man

> Nesse site você consegue encontrar informações de personagens para testar os end-points: https://marvel.fandom.com/pt-br/wiki/Categoria:Personagens

Essa é a estrutura JSON para fazer o POST e o PUT:

```json
{
  "nome": "Peter Benjamin Paker",
  "identidade": "Spider-Man",
  "genero": "Masculino",
  "imagem": "https://static.wikia.nocookie.net/marvel/images/9/96/Friendly_Neighborhood_Spider-Man_Vol_2_8_Granov_Variant_Textless.jpg/revision/latest/scale-to-width-down/333?cb=20190906235758&path-prefix=pt-br"
}
```

Obrigado por testar e utilizar minha API, volte sempre!
