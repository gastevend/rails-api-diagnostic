# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The backend is for updating, creating, reading, and deleting data.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The Model
```

Which layer in the MVC pattern communicates with the model?

```md
The Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Great question. Its the way of the dianosour some might say.
```

What does C.R.U.D stand for?

```md
Create. Read. Update. Destroy.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
The Model
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
update, destroy, create, show, index
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
1. Client makes the request to the server
2. Server recieves the request info and communicates that to the people controller
3. the people controller then sends that information to the show action in the model
4. the model performs the show action on person with id: 1 and sends a response back to the contoller
5. the controller then relays that response back to the server
6. the server then lets the client know what the response is.
```

What is the command to generate a new rails-api app?

```bash
rails new blah
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
1. db:drop
2. db:create
3. db:migrate
4. db:seed
5.
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
psql
CREATE TABLE pet (
  id SERIAL PRIMARY KEY,
  name TEXT,
  age DATE); #not an interger :)
```
