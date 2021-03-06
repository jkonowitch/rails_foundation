source :rubygems

gem 'rails', '~> 3.2.8'

# Database
gem 'pg'

# Authentication
gem 'devise'
gem 'devise-encryptable'

# JavaScript Frameworks
gem 'jquery-rails', '>= 2.0.2'

# Decorators
gem 'draper'

# Image uploading and processing.
gem 'dragonfly'
gem 'fog'
gem 'rack-cache', require: 'rack/cache'

# API Keys & Secrets
gem 'secretive'

# Include FactoryGirl in all environments in order
# to use factories in seeds.rb.
gem 'factory_girl'

# Fake data.
gem 'ffaker'

gem 'bootstrap-sass'

gem 'haml-rails'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

group :development do
  gem 'guard'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'guard-migrate'
  gem 'rb-fsevent', require: false
end

group :development, :test do
  gem 'sqlite3'
  gem 'pry'
  gem 'rspec-rails'
end

group :test do
  gem 'spork-rails'
  gem 'shoulda-matchers'
  gem 'turnip'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'launchy'
  gem 'vcr'
  gem 'webmock'
end