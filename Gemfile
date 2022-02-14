source 'https://rubygems.org'

#don't upgrade
gem 'rails', '5.2.6.2'

ruby '2.2.4'

# Authentication gem
gem 'devise', '>= 4.4.2'

# Bundle edge Rails instead:
# gem 'rails', github: 'rails/rails'

gem 'sqlite3'
gem 'foreman'
gem 'crack', '0.3.1'

# Pry for Rails, not in dev group in case running via prod/staging @ a training
gem 'pry-rails'

group :development, :mysql do
  gem 'brakeman'
  gem 'bundler-audit'
  gem 'guard-brakeman'
  gem 'guard-livereload'
  gem 'guard-rspec'
  gem 'guard-shell'
  gem 'pry'
  gem 'rack-livereload'
  gem 'rb-fsevent'
  gem 'travis-lint'
  gem 'better_errors'
  gem 'binding_of_caller'
end

gem 'gauntlt'

gem 'simplecov', :require => false, :group => :test

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
gem 'sass-rails', '>= 5.0.5'
gem 'coffee-rails', '>= 4.2.2'
gem 'jquery-fileupload-rails', '>= 0.4.6'
gem 'uglifier'
gem 'turbolinks' , '>= 2.5.3' # New for Rails 4.0

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', :platforms => :ruby

gem 'jquery-rails', '>= 4.0.5'

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
gem 'mailcatcher'

#For Rails 4.0
#group :doc do
#  # bundle exec rake doc:rails generates the API under doc/api.
#  gem 'sdoc', require: false
#end
