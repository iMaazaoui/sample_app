source 'https://rubygems.org'

gem 'rails', '4.1.0'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'jquery-rails'
gem 'turbolinks'
gem 'protected_attributes'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'childprocess'
  gem 'spork-rails'
  gem 'libnotify'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

group :test do
  gem 'capybara', '1.1.4'
  gem 'factory_girl_rails'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'
  # gem 'launchy', '2.1.0'
  # gem 'rb-fsevent', '0.9.1', :require => false
  # gem 'growl', '1.0.3'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end