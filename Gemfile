source 'https://rubygems.org' do
  gem 'rails'
  gem "sass-rails", "~> 5.0.1"
  gem 'mysql2'
  gem 'uglifier'
  gem 'bundler-audit'
  gem "slim"
  gem "kaminari"
  gem 'activemodel', '~>4.0'
  gem 'activesupport', '~>4.0'

  # Front end
  gem 'jquery-rails'
  gem 'modernizr-rails'
  gem 'bootstrap-sass'

  # Send HTTP secure headers
  gem 'secure_headers'

  # Exception notification
  gem 'exception_notification'

  # Exceptions
  gem 'rollbar'
  gem 'pagerduty'

  # Connect to Svalbard
  gem 'httpclient', '>= 2.7.1'

  group :test do
    gem 'timecop'
    gem 'simplecov', require: false
    gem 'codeclimate-test-reporter', require: nil
    gem 'rspec-rails'
    gem 'webmock'
    gem "capybara"
    gem 'poltergeist'
    gem 'cucumber-rails', require: false
    gem 'factory_girl_rails'
    gem 'database_cleaner'
    gem 'launchy'
    gem 'brakeman'
  end

  group :development do
    gem 'puma'
    gem 'binding_of_caller'
    gem 'better_errors'
    gem 'pry'
    gem 'listen'
    gem 'unicorn'
    gem 'quiet_assets'
    gem 'travis'
  end

  group :deploy do
    gem 'capistrano-rvm'
  end

  group :development, :test do
    gem "guard"
    gem 'guard-bundler'
    gem 'guard-rails'
    gem 'guard-rspec'
    gem "guard-jasmine"
  end
end
