# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
A backend's purpose is to handle and respond to requests from the client, or front end.  It handles things like business logic and database interactions.  The back end essentially enables the front end experience.
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
Views are the presentation layer and are essentially visual representations of models.  They render the models into one or more formats, such as XML.
```

What does C.R.U.D stand for?

```md
Create
Read
Update
Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
They can be found within the controller.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Index
Show
Create
Update
Destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
-Request is sent to the web server
-The router directs the request to the people controller
-The controller directs the request to the appropriate model
-The model returns data to the controller
-The controller returns data to the web server
-The web server displays a response for the user
```

What is the command to generate a new rails-api app?

```bash
rails new
```

What is the command to start an instance of a rails server?

```bash
bundle exec rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
db:drop
db:create
db:seed
db:setup
db:reset
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails generate scaffold Pet name: string age: integer
```
