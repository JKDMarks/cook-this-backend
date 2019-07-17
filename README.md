# <img src="https://i.imgur.com/FtclHY5.png" height="30" width="30" alt="chef hat"> Cook This
A website for scraping recipes and cooking along with them.

**[(Link to Frontend)](https://github.com/Jeffrey-Marks/cook-this-frontend)**

## Inspiration

I love cooking and I love adding new favorite recipes to my collection. This is a place to store all of those favorites and also cook along with them.

## Features

Given a recipe URL, creates an ActiveRecord Recipe instance and adds each ingredient and step as an associate (Recipe has_many Ingredients, Steps).

## Built With

* [Ruby on Rails](https://rubyonrails.org/) - Used as a RESTful API built on top of a SQL database
* [PostgreSQL](https://www.postgresql.org/) - Database
* [BCrypt](https://github.com/codahale/bcrypt-ruby) - Password hashing
* [JWT](https://github.com/jwt/ruby-jwt) - JSON Web Token OAuth

## Notes

Secondary name is `this.cook()`.
