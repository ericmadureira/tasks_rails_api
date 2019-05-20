# Todo List Rails API

## Technologies used
* Ruby: **2.5.5**
* Rails: **5.2.3**
* database: **postgres**
* Made to work with https://github.com/ericmadureira/tasks_client

## Setup
1. Open terminal
2. Run `git clone https://github.com/ericmadureira/tasks_rails_api`
3. Run `cd taks_rails_api`
4. In config/database.yml change the definitions to match your database

From here on things get different if you want to use Docker or not:

* Install using Docker
5. Run `docker build .`
6. Run `docker-compose up`
7. Open another terminal and run `docker-compose run bundle exec rake db:create db:migrate`
8. Your rails API is ready to serve at localhost:3001
* Install without Docker
5. Run `bundle install`

## References
* https://docs.docker.com/compose/rails/
* https://onebitcode.com/crud-com-rails-e-react/ (pt-BR)