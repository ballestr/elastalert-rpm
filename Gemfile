# encoding: utf-8
source 'https://rubygems.org'

gem 'inspec'

group :test do
  gem 'bundler', '~> 1.5'
  gem 'minitest', '~> 5.5'
  gem 'rake', '~> 10'
  gem 'rubocop', '~> 0.33.0'
  gem 'simplecov', '~> 0.10'
end

group :integration do
  gem 'test-kitchen', '~> 1.4'
  gem 'kitchen-ansible'
  gem 'kitchen-vagrant'
  gem 'kitchen-docker'
  gem 'kitchen-inspec'
  gem 'concurrent-ruby', '~> 0.9'
end
