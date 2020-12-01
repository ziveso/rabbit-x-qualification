# RabbitX is hiring!

### Your assignment is

- Write the multi functions todolist application using one of the specific javascript library.

There are **10** points totals (+1 additional), you will need to complete **at least 7 points.**

### Example

[https://www.w3schools.com/howto/howto_js_todolist.asp](https://www.w3schools.com/howto/howto_js_todolist.asp)

### Moreover

- If the todo has **only number**, you will need to sum all of the number and show the result. ( where ever you want to ),
- If there is **not a number** ( String, String plus number, whatever that is not a number ), you will need to concat all the todos and show the result as well.
- You will also need to send all the actions to our backend via **REST API**.

### Requirements ( Score )

1. Use **_React.js_** (1 pts) or **_React-Native_**. (3 pts)
2. Use **_Mobx_** as global state management (2 pts) and use the correct type of actions. (+1 pts)
3. Complete the application with **_all functions_**. (2 pts)
4. Connect the backend using **_REST API_**. (2 pts)

Invite guy.thitiwat@rabbitstale.com to the repository when you finish.

#### Additional ( +1 pts )

- If you're using React.js

  - Good commit messages and Deploy using any provider.
  - Include the url in readme.md

- If you're using React-Native

  - Upload .apk file to firebase app distribution.
  - Invite guy.thitiwat@rabbitstale.com to android tester.

### Getting started!

`const API_URL = "http://assignment.picklebutnotcucumber.com"`

Note: you don't need to do the login part, request it anywhere you want and hard code the token.

> // get the bearer token by username and password or create one if not exists.

1. **POST /login**

   request

   `const { username, password } = req.body`

   response

   `{ authToken: "xxxxxx", status: "register" }`

> // list current todos.

2. **XXX /**

   response

   `[{ todo: "xxxx", status: "pending" }, { todo: "xxxx", status: "done" }]`

> // post new todo.

3. **XXX /**

   request

   `const { todo } = req.body`

   response

   `{ _id: "xxxxx", todo: "xxxx", status: "pending" }`

> // update todo status by id

4. **XXX /:id**

   request

   `const { status } = req.body`

   response

   `{ _id: "xxxxx", todo: "xxxx", status: "status" }`

> // delete todo by id

5. **XXX /:id**

   response

   `done`
