# Toy App Make by Ruby on Rails (RoR)

A [tutorial project](https://www.railstutorial.org/book/toy_app) for start to learn Ruby on Rails.

## Note

- Running Environment - Tutorial work with latest ruby and rails (Ruby v2.6.3 /Rails v5.2.3)

- To Run this project locally

  - Install latest version of Ruby & Rails
  - `git clone git@github.com:kelvin8773/rails-toy-app.git` to local computer.
  - `$ bundle install --without production` run as development environment. (can't run as production environment because it require postgresql setup locally)
  - `$ rails db:migrate` create the new db locally.
  - `$ rails server` run the server at http://localhost:3000.

- Deploy to Heroku
- `$ heroku login` if you are not login already.
- `$ heroku git:clone -a toy-app-123` change the name of `toy-app-123` to your heroku app's name (try to create the app before either from web or CLI).
- `$ git add .`
- `$ git commit -am "make some changes"`
- `$ git push heroku master`

Please Note: App run on Heroku will run on **Production** environment and use **postgresql** as backend db.

## Links

- [Ruby on Rails Tutorials (Rails 5)](https://www.railstutorial.org/book)

- [Project Demo](https://toy-app-254.herokuapp.com)
