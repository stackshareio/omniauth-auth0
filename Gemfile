source 'https://rubygems.org'

gemspec

gem 'gem-release'
gem 'jwt'
gem 'rake'

group :development do
  gem 'dotenv'
  gem 'pry'
  gem 'rubocop', require: false
  gem 'shotgun'
  gem 'thin'
end

group :development, :test do
  gem 'sinatra'
end

group :test do
  gem 'guard-rspec', require: false
  gem 'listen', '~> 3.1.5'
  gem 'rack-test'
  gem 'rspec', '~> 3.5'
  gem 'codecov', require: false
  gem 'simplecov'
  gem 'webmock'
end
