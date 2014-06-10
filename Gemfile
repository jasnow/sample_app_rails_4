source 'https://rubygems.org'
ruby '2.1.2'

gem 'rails', '4.0.5'
gem 'sprockets', '2.11.0'

gem 'bootstrap-will_paginate'
gem 'bootstrap-sass'

gem 'bcrypt'
gem 'faker'
gem 'will_paginate'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :development, :test do
  gem 'rspec-rails'
  gem 'rspec-its'
  gem 'sqlite3'

  # The following optional lines are part of the advanced setup.
  gem 'guard-rspec'
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
end

group :test do
  gem 'cucumber-rails', :require => false
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'simplecov', :require => false

  # Uncomment these lines on Linux.
  gem 'libnotify'

  # Uncomment this line on OS X.
  # gem 'growl', '1.0.3'
  #
  # Uncomment these lines on Windows.
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
  # gem 'wdm', '0.1.0'
end

group :doc do
  gem 'sdoc', require: false
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
