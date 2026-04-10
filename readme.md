# Projeto da aula de DS


### Endpoints da API

#### Rotas de Pessoa (`/person`)
- **GET /person/people**: Retorna todas as pessoas.
- **POST /person/people**: Cria uma nova pessoa.
- **GET /person/people/:id**: Retorna uma pessoa específica pelo ID.
- **PUT /person/people/:id**: Atualiza uma pessoa pelo ID.
- **DELETE /person/people/:id**: Exclui uma pessoa pelo ID.

#### Rotas de Jogo (`/game`)
- **GET /game/game**: Retorna todos os jogos.
- **POST /game/game**: Cria um novo jogo.
- **GET /game/game/:id**: Retorna um jogo específico pelo ID.
- **PUT /game/game/:id**: Atualiza um jogo pelo ID.
- **DELETE /game/game/:id**: Exclui um jogo pelo ID.

Esses endpoints são configurados no arquivo router.js e utilizam os controladores correspondentes em controllers. Para mais detalhes sobre a implementação, consulte os arquivos de controlador.
