## Endpoints

This is a test for a Fake API project, proposed by Kenzie Academy with the purpose of training and fixating what was learnt in the
past few assignments.

### Cadastro <br>

POST /register <br/>

You may register a new user with the following format:

```json
{
  "email": "test@mail.com",
  "password": "123456",
  "name": "YourNameOfChoosing",
  "age": "InputANumberHere"
}
```

### Login <br>

POST /login <br/>

You may login using the following format:

```json
{
  "email": "test@mail.com",
  "password": "123456"
}
```

### Posts

POST /posts <br/>

You may create a new post with the following format:

```json
{
  "message": "YourPostMessage",
  "author": "CouldBeYourNameOrAnyoneElse's"
}
```

### Secret -- REQUIRES AUTH

GET /secret

You may reach the secret link but you must be logged in.
