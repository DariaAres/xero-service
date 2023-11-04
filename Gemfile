source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.7", ">= 7.0.7.2"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Bundle and transpile JavaScript [https://github.com/rails/jsbundling-rails]
gem "jsbundling-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Bundle and process CSS [https://github.com/rails/cssbundling-rails]
gem "cssbundling-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
gem "image_processing", "~> 1.2"

# Validations for Active Storage (presence) [https://github.com/igorkasyanchuk/active_storage_validations]
gem 'active_storage_validations'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]

  # A fixtures replacement with a straightforward definition syntax [https://github.com/thoughtbot/factory_bot_rails]
  gem 'factory_bot_rails'

  # Pry is a runtime developer console and IRB alternative with powerful introspection capabilities. [https://github.com/pry/pry]
  gem 'pry', '~> 0.14.2'

  # It's a library for generating fake data such as names, addresses, and phone numbers. [https://github.com/faker-ruby/faker]
  gem 'faker'

  # Capybara helps you test web applications by simulating how a real user would interact with your app. [https://github.com/teamcapybara/capybara]
  gem 'capybara'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # A Ruby gem to load environment variables from `.env` [https://github.com/bkeepers/dotenv]
  gem 'dotenv-rails'
end

group :test do
  # Selenium implements the W3C WebDriver protocol to automate popular browsers. [https://github.com/SeleniumHQ/selenium/wiki/Ruby-Bindings]
  gem "selenium-webdriver"

  # Run Selenium tests more easily with automatic installation and updates for all supported webdrivers. [https://github.com/titusfortner/webdrivers]
  gem "webdrivers"
end