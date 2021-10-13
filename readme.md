# TodoApi

### Projeto

<p>Uma api desenvolvida como desafio da Trilha nodeJs do Ignite na Rocketseat.
Com ela voce pode criar lista de tarefas, marcar como resolvida. Apagar/Editar uma tarefa.
</p>

### 🛠 Tecnologias

- NodeJs

### 🛠 Frameworks

- cors
- express
- uuid

🔗 Install & Run

```bash
 # clone repository
  git clone https://github.com/renatobh83/ignite-template-conceitos-do-nodejs..git

  # enter web folder
  cd ignite-template-conceitos-do-nodejs.
  # download dependencies
  yarn

  # running / dev:
  yarn dev

  # start
  yarn start

  # run tests
  yarn test
```

```sh
Rotas

Post /users - Params user e username

# Todas rotas seguintes deve ser necessario enviar no cabecalho o username


Get /todos - Retorna a lista de tarefas do usuario

Post /todos - Cria uma nova tarefa para o usuario.
    - Params : title, deadline

Put /todos/:id - Atualiza uma tarefa
  - Params : title, deadline

Patch /todos/:id/done -  Muda o status de uma tarefa para True

Delete /todos/:id - Apaga uma tarefa
```
