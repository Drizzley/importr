source 'https://rubygems.org'
# ruby "~> 2.5.1" # min "~> 2.3.7" which is not available on Heroku-18
gem 'dotenv-rails', require: 'dotenv/rails-now', groups: [:development, :test]


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '< 5.0' # go to 5.1.6? pg_sequence bug is fixed in 5.1.4
ruby '2.5.7'
gem 'pg', '~> 0.18.4'
gem 'oj', '~> 2.18.5'
gem 'rollbar', '~> 2.15.6'

group :development do
#  gem 'guard-livereload', '~> 2.4', require: false # security
#  gem 'rerun' # security
  gem 'annotate'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

gem 'sinatra'
gem 'redis'
gem "bower-rails", "~> 0.9.2"

gem 'simple_form' # for security, ">= 5.0.0"
gem 'faraday'
gem 'sidekiq'
# gem 'sidekiq-unique-jobs', '~> 4.0.18'
gem 'puma'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'pry'
  gem 'pry-byebug'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 1.7.2'
end
