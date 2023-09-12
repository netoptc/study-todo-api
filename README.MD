# study-todo-api

This is a study project of a car rental api

## 📘 Tech Stack

**Server:**

- JavaScript
- Node
- Express
- Jest

## ⭐ Installation

Install my-project with npm

```bash
  yarn install
  yarn dev
```

## ✅ Running Tests

To run tests, run the following command

```bash
  yarn test
```

## 📌 Requirements

- [x] POST /users
      A rota deve receber name, e username dentro do corpo da requisição
- [x] GET /todos
      A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e retornar uma lista com todas as tarefas desse usuario
- [x] POST /todos
      A rota deve receber title e deadline dentro do corpo da requisição e, uma propriedade username contendo o username do usuário dentro do header da requisição. Ao criar um novo todo, ele deve ser armazenada dentro da lista todos do usuário que está criando essa tarefa.
- [x] PUT /todos/:id
      A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e receber as propriedades title e deadline dentro do corpo. É preciso alterar apenas o title e o deadline da tarefa que possua o id igual ao id presente nos parâmetros da rota.
- [x] PATCH /todos/:id/done
      A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e alterar a propriedade done para true no todo que possuir um id igual ao id presente nos parâmetros da rota.
- [x] DELETE /todos/:id
      A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e excluir o todo que possuir um id igual ao id presente nos parâmetros da rota.
