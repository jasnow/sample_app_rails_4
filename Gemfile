# frozen_string_literal: true

source 'https://rubygems.org'

gem 'rails', '4.0.13'

gem 'bcrypt'
gem 'bootstrap-sass'
gem 'bootstrap-will_paginate'
gem 'faker'
gem 'jbuilder'
gem 'jquery-rails'
gem 'sassc-rails'
gem 'sprockets'
gem 'turbolinks'
gem 'uglifier'
gem 'will_paginate'

group :doc do
  gem 'sdoc', require: false
end

group :development, :test do
  gem 'childprocess'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'rspec-its'
  gem 'rspec-rails'
  gem 'rubocop-rspec'
  gem 'spork-rails'
  gem 'sqlite3', '1.3.13' # 2/7/2019: LOCKED DOWN
end

group :test do
  gem 'capybara'
  gem 'cucumber'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false

  # Uncomment these lines on Windows.
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
  # gem 'wdm', '0.1.0'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
