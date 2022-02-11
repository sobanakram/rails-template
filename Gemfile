source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "~> #{`cat .ruby-version`.strip}"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem "rails", "~> 6.1"

gem 'stimulus-rails', "~> 0.2"
# Use Postgres as the database for Active Record
gem "pg", "~> 1.2"
# Use Puma as the app server
gem "puma", "~> 5.6"
# Use SCSS for stylesheets
gem 'sass-rails', "~> 6.0"
gem 'sprockets', "~> 3.7"
gem 'sprockets-rails', "~> 3.2", require: 'sprockets/railtie'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', "~> 4.2"
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', "~> 5.2"
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.7'

gem 'active_storage_base64', "~> 1.2"
gem 'acts_as_tenant', "~> 0.5"
gem 'aws-sdk-s3', "~> 1.89", require: false
gem 'data-confirm-modal', "~> 1.6"
gem 'inline_svg', "~> 1.7"
gem 'simple_form', "~> 5.1"

# For searching
gem 'pagy', "~> 3.11"
gem 'ransack', "~> 2.4"

gem "devise", "~> 4.7"

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', "~> 1.7", require: false

gem 'bootstrap', '~> 5.0.0.beta2'

group :development, :test do
  gem "letter_opener", "~> 1.7"
  gem "standard", "~> 0.13"
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', "~> 11.1", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'rename', "~> 1.0"
  gem "annotate", "~> 3.1"
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', "~> 4.1"
  gem 'listen', "~> 3.4"
  gem "better_errors", "~> 2.9"
  gem "binding_of_caller", "~> 1.0"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', "~> 2.1"
  gem 'spring-watcher-listen', "~> 2.0"

  # For deployment
  gem 'capistrano', "~> 3.15"
  gem 'capistrano-bundler', "~> 2.0", require: false
  gem 'capistrano-rails', "~> 1.6", require: false
  gem 'capistrano-rails-console', "~> 2.3", require: false
  gem 'capistrano-rails-tail-log', "~> 0.1", require: false
  gem 'capistrano-rvm', "~> 0.1", require: false
  gem 'capistrano3-puma', "~> 5.0", require: false
  gem 'capistrano-yarn', "~> 2.0", require: false
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', "~> 3.35"
  gem 'selenium-webdriver', "~> 3.142"
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers', "~> 4.6"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
