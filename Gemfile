source 'http://rubygems.org'

gem 'rails', '3.2.14'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels'  # some pre-fabbed step definitions
  gem 'database_cleaner'  # to clear Cucumber test db between runs
  gem 'capybara'          # lets Cucumber pretend to be a web browser
  gem 'launchy'           # useful debugging aid for user stories
  gem 'sqlite3'
  gem 'ruby-debug19'
  gem 'capybara'
  gem 'rspec-rails'
  gem 'simplecov'
  gem 'ZenTest'
end

group :production do
#  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'therubyracer', '~> 0.12.0'
  gem 'sass-rails', '~> 3.2.6'
  gem 'coffee-rails', '~> 3.2.2'
  gem 'uglifier'
end

gem 'jquery-rails'
gem 'haml'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'
