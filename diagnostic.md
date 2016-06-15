# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
stores everything that makes the front end run
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
model
```

Which layer in the MVC pattern communicates with the model?

```bash
controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
 views are just what a users sees
```

What does C.R.U.D stand for?

```bash
create read update delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
in the controller
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
index, new, create, show, update, destroy
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
client
server
person controller
model controller
person controller
server
client
```

What is the command to generate a new rails-api app?

```bash
rails new commandsapp
```

What is the command to start an instance of a rails server?

```bash
rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
rake db:drop
rake db:create
rake db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
generate scaffold pet name:string age:integer
```

List two advantages of using serializers? (2 bullet points)

```bash
makes it safer and easier to use
```
