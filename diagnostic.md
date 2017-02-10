# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
//  server, an application and a database. The back end is where the technical processes happen, as opposed to the front end, which is usually where the user's interaction occurs.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
// the model
```

Which layer in the MVC pattern communicates with the model?

```md
// the controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
// the controller is the view, it responds directly back to the client with the output
```

What does C.R.U.D stand for?

```md
// Create, Read, Update, Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
// it is found in the controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
// GET => INDEX
  GET => SHOW
  POST => CREATE
  PUT/PATCH => UPDATE
  DELETE => DESTROY
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
// 1.user sends GET request, goes to router
  2. router sends to controller
  3. controller sends to model
  4. model acesses database
  5. database sends data to model
  6. model sends to controller
  7. controller sends back to user
```

What is the command to generate a new rails-api app?

```bash
// bin/rails generate <name>
```

What is the command to start an instance of a rails server?

```bash
// bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
//
1. db.drop
2. db.create
3. db.migrate
4. db.seed
5. I only saw 4 commands
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// rails generate scaffold PET [  name[:TEXT] age[:INTEGER]]
```
