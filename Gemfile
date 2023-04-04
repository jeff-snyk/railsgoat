source 'https://rubygems.org'

#don't upgrade
gem 'rails', '6.1.7.3'

ruby '2.2.4'

# Authentication gem
gem 'devise', '>= 4.7.1'

# Bundle edge Rails instead:
# gem 'rails', github: 'rails/rails'

gem 'sqlite3'
gem 'foreman'
gem 'crack', '0.3.2'

# Pry for Rails, not in dev group in case running via prod/staging @ a training
gem 'pry-rails'

group :development, :mysql do
  gem 'brakeman', '>= 3.3.0'
  gem 'bundler-audit'
  gem 'guard-brakeman'
  gem 'guard-livereload', '>= 2.5.2'
  gem 'guard-rspec'
  gem 'guard-shell'
  gem 'pry'
  gem 'rack-livereload'
  gem 'rb-fsevent'
  gem 'travis-lint'
  gem 'better_errors', '>= 2.8.0'
  gem 'binding_of_caller'
end

gem 'gauntlt', '>= 1.0.13'

gem 'simplecov', '>= 0.12.0', :require => false, :group => :test

group :development, :test, :mysql do
  gem 'launchy'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'poltergeist'
  gem 'rspec-rails', '2.14.2'
  gem 'test-unit'
end

group :mysql do
  gem 'mysql2'
end

# Gems used only for assets and not required
# in production environments by default.
gem 'sass-rails', '>= 6.0.0'
gem 'coffee-rails', '>= 4.2.2'
gem 'jquery-fileupload-rails'
gem 'uglifier'
gem 'turbolinks' , '>= 5.0.0' # New for Rails 4.0

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', :platforms => :ruby

gem 'jquery-rails', '>= 4.4.0'

# To use ActiveModel has_secure_password
 gem 'bcrypt'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
 gem 'unicorn'

# Pow related gem
gem 'powder'

gem 'aruba'
#gem 'minitest', '~> 4.0', :require=> "minitest/autorun"

#gem 'minitest'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

gem 'execjs'
gem 'therubyracer'

# Add SMTP server support using MailCatcher
gem 'mailcatcher', '>= 0.6.5'

#For Rails 4.0
#group :doc do
#  # bundle exec rake doc:rails generates the API under doc/api.
#  gem 'sdoc', require: false
#end
