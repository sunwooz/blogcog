# 2015-07-23 RICHARD:
# Various changes to prior version, and you might still need to run these to get it sorted out.
# bundle , bundle,  bundle update , gem update, bundle update, bundle
source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 4.2.3'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

# Use SCSS for stylesheets
gem 'sass-rails' #, '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier' # , '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails' # , '~> 4.0.0'
gem 'intercom-rails'
gem 'taps'
gem 'activeadmin', github: 'gregbell/active_admin'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder' # , '~> 1.2'

gem 'devise'
gem 'bootstrap-sass-rails'
gem 'carrierwave'
gem 'json'
gem 'airbrake'
gem 'koala'
gem 'omniauth'
gem 'omniauth-oauth2'
gem 'omniauth-google-oauth2'
gem 'rmagick'
gem 'simple_form'
gem 'pg'
gem 'thin'

gem 'eventmachine' # , '>=1.07'

group :development, :test do
  gem 'byebug'
  #gem 'annotate'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'quiet_assets'

  #gem 'timecop'
end

group :development, :test do
  gem 'factory_girl_rails' # https://github.com/thoughtbot/factory_girl/blob/master/GETTING_STARTED.md
  gem 'guard' # https://github.com/guard/guard
  gem 'guard-cucumber'
  gem 'guard-rspec'
end


group :test do
  gem 'cucumber-rails', :require => false # https://github.com/cucumber/cucumber-rails
  gem 'database_cleaner' # https://github.com/bmabey/database_cleaner
  gem 'shoulda-matchers' # https://github.com/thoughtbot/shoulda-matchers
  gem 'launchy'
end


group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
