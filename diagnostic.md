# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The backend is responsible for calculations, business logic, database interactions, etc.  It is what makes the application run.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
Model
```

Which layer in the MVC pattern communicates with the model?

```md
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Views only read what the controller gives them.
```

What does C.R.U.D stand for?

```md
'create', 'read', 'update', and ‘destroy’
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
The MVC pattern is a way of divding the four steps.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
// your response here
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
- make route ti specify what to do when a request comes in
- define controller to handle the request
- generate model
- run migrations
- use Active Recording to show the data
```

What is the command to generate a new rails-api app?

```bash
// your response here
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
destory
create
update


```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
