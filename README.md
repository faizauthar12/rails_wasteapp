# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


### Seed Untuk Roles
- Setelah migrate, seed dulu, karena untuk pembuatan user harus memiliki role id, jadi harus inisiali data di role dulu baru dari role tersebut kita gunakakan id-nya untuk pembuatan user (nantinya dapat token auth untuk login)

reset migrate database
> rake db:migrade:redo

seed
> rake db:seed