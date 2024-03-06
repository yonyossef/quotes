# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies
  apt install postgresql
  
* Configuration
  sudo -i -u postgres
  psql
  CREATE ROLE quote_editor_development WITH LOGIN PASSWORD 'quote_editor_password';
  ALTER ROLE quote_editor_development CREATEDB;

* Database creation
  export QUOTE_EDITOR_DATABASE_PASSWORD=quote_editor_password
  - edit peer to md5 for password authentication login:
    vim /etc/postgresql/14/main/pg_hba.conf
  service postgresql restart

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

