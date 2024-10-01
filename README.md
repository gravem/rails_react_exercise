# README

Following this guide: https://rubyroidlabs.com/blog/2023/11/how-to-use-ruby-on-rails-with-react-in-2024/

Setup: `$ rails new rails_react_exercise -d postgresql -j esbuild -c bootstrap -T`
Connecting application to databases: `$ rails db:create`
Created database 'rails_react_exercise_development'
Created database 'rails_react_exercise_test'

2. Installed react with `$ yarn add react react-dom react-router-dom`
3. Creating homepage: `$ rails g controller Homepage index`

- Change get 'homepage/index' to root 'homepage#index' in `config/routes.rb`
- Removed code in `~/rails_react_exercise/app/views/homepage/index.html.erb`

4. Configure React as the Rails frontend.
   Start application with bin/dev

<!-- This README would normally document whatever steps are necessary to get the
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

* ... -->
