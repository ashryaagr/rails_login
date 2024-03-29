source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.2'
#added jquery support
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
# used to create fake users on our site (can be used only by us and not the users)
gem 'faker', '~> 1.9', '>= 1.9.1'
# state of art hash function to secure our password
gem 'bcrypt', '~> 3.1', '>= 3.1.12'
# pagination
gem 'will_paginate', '~> 3.1', '>= 3.1.6'
gem 'bootstrap-will_paginate', '~> 1.0'
# adding bootstrap support
gem 'bootstrap-sass', '3.3.7'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '~>3.0.4'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'duktape'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Make errors better looking
gem 'better_errors', '~> 2.5'

# Bulma css
gem 'bulma-rails', '~> 0.7.2'

# Simple form
gem 'simple_form', '~> 4.1'
gem 'adorable_avatars'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '~> 1.3', '>= 1.3.13'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  # Guard is a command line tool to easily handle events on file system modification
  gem 'guard', '~> 2.15'
  # automatically reloads browser when 'view' files are modified.
  gem 'guard-livereload', '~> 2.5', '>= 2.5.2', require: false
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

group :production do
  gem 'pg', '~> 1.1', '>= 1.1.4'
  gem 'rails_12factor'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
