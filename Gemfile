source 'https://rubygems.org'
ruby '2.3.0'

gem 'rails', '4.2.1'
gem "rack-handlers"
gem 'pg'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'geocoder'
gem 'figaro'
gem 'rest-client'
gem 'addressable'
gem 'unicorn'
gem 'redis'
# Resque for async tasks
gem 'resque', "~> 1.22.0"

group :production do
  gem 'sentry-raven'
end

group :development do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
end

group :test do
  gem 'faker'
  gem 'capybara'
  gem 'guard-rspec'
  gem 'launchy'
end

group :development, :test do
  gem 'pry-rails'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'annotate'
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end
