source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
# gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Clearance
gem 'clearance'
# Figaro
gem 'figaro'
# OmniAuth Google OAuth 2.0
gem 'omniauth'
gem 'omniauth-google-oauth2'
# Boostrap & Sass
gem 'bootstrap'
gem 'autoprefixer-rails'

gem 'jquery-rails'

# Act As Taggable
gem 'acts-as-taggable-on'

# Faker
gem 'faker'

# Google Custom Search API
gem "google_custom_search_api"

# ImageSuckr
gem 'image_suckr'

# Kaminari (Pagination)
gem 'kaminari'

# Country-Select
gem 'country_select', '~> 3.1'

# CarrierWave
gem 'carrierwave', '~> 1.0'

# CarrierWave + AWS
gem 'carrierwave-aws'

# Mini Magick
gem 'mini_magick'

# Dropzone JS
gem 'dropzonejs-rails'

# AWS SDK Rails
gem 'aws-sdk-rails'

# moment
gem 'momentjs-rails'

# Braintree
gem 'braintree'

# Letter Opener
gem "letter_opener", :group => :development

# Sidekiq
gem 'sidekiq'

# PG_SEARCH
gem 'pg_search'

# RBP
gem 'rails_best_practices'

gem 'rails_12factor'

group :production, :development do
  gem 'skylight'
end

gem 'unicorn'

gem 'newrelic_rpm'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
