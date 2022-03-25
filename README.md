# Todos API

Fully-fledged API for managing tasks in form of to-do list. 
Fully tested with RSpec testing framework (as well as other libraries
such as FactoryBot or Faker)

#Installation 

Download project and run 

```shell
bundle install
rake db:migrate
rails s
``` 

#Features

Todos API provides endpoints to performing CRUD actions on todo items.
It also provides extended requests authorization using Json Web Token.


#Testing

To run RSpec tests just type
```ruby
rspec
``` 
in the main project folder.

---

Project based on Rails API tutorial by Austin Kabiru presented on
https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-one
