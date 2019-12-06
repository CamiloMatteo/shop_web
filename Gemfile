source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'puma', '~> 3.12'
gem 'rails', '~> 5.2.3'

# DB
gem 'pg', '>= 0.18', '< 2.0'

# Front
gem 'bootsnap', '>= 1.1.0', require: false
gem 'bootstrap-sass', '>= 3.4.1'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks'
gem 'uglifier', '>= 1.3.0'

# Back
gem 'bcrypt', '~> 3.1.7'
gem 'cancancan'
gem 'devise'
gem 'jbuilder', '~> 2.5'
gem 'rolify'
gem 'sdoc', '~> 0.4.0', group: :doc

group :development, :test do
  gem 'pry-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'chromedriver-helper'
  gem 'selenium-webdriver'
end
