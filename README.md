# EtchASketchBE
# EtchASketchBE
Built by Minh Chau Ha
and
Ryan Denlinger

This is the Back-end for Etch-A-Fetch.
You will need this and the Front-end:

front-end-link: https://github.com/minhl337/EtchASketchFE

deployed link: https://etchafetch.herokuapp.com/

To get this app running.

1) Fork and Clone

2) Make sure you have postgresgl installed and have your password ready.

change the following lines

./config/database.yml

```ruby 
default: &default
  adapter: postgresql
  encoding: unicode
  
  pool: <%= ENV.fetch("RAILS_MAX_THREADS") { 5 } %>
  password: <YOUR PASSWORD>
  username: postgres
  ```

3) run these terminal commands
```
bundle install
rails db:create
rails db:migrate
rails s
```

Your Back-end is now ready to server the front end.
Get the Front end here:

https://github.com/minhl337/EtchASketchFE

Video of running application:
https://youtu.be/AFdqrJzG5_8
