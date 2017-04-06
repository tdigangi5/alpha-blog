# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Database creation
  - `docker-compose run app rake db:create`
  - `docker-compose run app rake db:schema:load db:seed`
* App Standing up
  - `docker-compose up -d`

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
pg_ctl -D /usr/local/var/postgres -l /usr/local/var/postgres/server.log start
* ...
