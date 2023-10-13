source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.0.6', '>= 6.0.6.1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.7'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'listen', '~> 3.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development, :test do
  gem 'dotenv-rails'
  gem "pronto", "~> 0.11.1"
  gem "pronto-annotations_formatter", git: 'https://github.com/emilio2hd/pronto-annotations_formatter'
  # gem "pronto-annotations_formatter", path: '../pronto-annotation/pronto-annotations_formatter'
  gem "pronto-rails_schema", "~> 0.11.0"
  gem "pronto-rubocop", "~> 0.11.5"
  gem "pronto-reek", "~> 0.11.1"
  gem "pronto-brakeman", "~> 0.11.2"
  gem 'pry'
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
  gem "faraday-retry", "~> 2.2"
end

group :test do
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'ffaker'
  gem 'rails-controller-testing'
  gem 'shoulda-matchers', require: false
  gem 'simplecov', require: false
end
