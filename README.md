# README

# Crazy4Cats

* Ruby version
    - Rails 7.0.6

* Gemas instaladas
    - gem "bootstrap", "~> 5.2"
    - gem "jquery-rails", "~> 4.6"
    - gem "popper", "~> 0.5.3"
    - gem "devise", "~> 4.9"
    - gem "font-awesome-sass", "~> 6.4.0"

* Configuración
    - rails generate devise User
    - rails g scaffold publications content:text
    - rails g migration AddUsersToPublications user:references
    - rails g model like publication:references user:references

* Database
    - Postgresql


