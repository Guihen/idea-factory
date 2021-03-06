source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

gem 'rails_12factor', group: :production # Used by heroku

# Twitter bootstrap: Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web.
gem 'bootstrap-sass', '~> 3.3.1.0'

# Twitter boostrap suggest: is a tool to parse CSS and add vendor prefixes to CSS rules using values from the Can I Use. This gem provides Ruby and Ruby on Rails integration with this JavaScript tool.
gem 'autoprefixer-rails'

# Gems to testing
group :development, :test do
  gem 'rspec-rails', '~> 3.0.0'
  gem 'factory_girl', '~> 4.5.0' # factory_girl provides a framework and DSL for defining and using factories - less error-prone, more explicit, and all-around easier to work with than fixtures.
  gem 'database_cleaner', '~> 1.3.0' # Factory girl suggest: Strategies for cleaning databases. Can be used to ensure a clean state for testing.
  gem 'capybara', '~> 2.4.4' # Capybara is an integration testing tool for rack based web applications. It simulates how a user would interact with a website
  gem 'simplecov', '~> 0.9.1', require: false # Code coverage for Ruby 1.9+ with a powerful configuration library and automatic merging of coverage across test suites
  #gem 'mocha', require: 'mocha/api' # Mocking and stubbing library with JMock/SchMock syntax, which allows mocking and stubbing of methods on real (non-mock) classes.
end

gem 'devise' # Devise is a flexible authentication solution for Rails based on Warden.