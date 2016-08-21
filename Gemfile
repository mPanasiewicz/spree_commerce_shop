source 'https://rubygems.org'
ruby '2.3.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7'
# Use sqlite3 as the database for Active Record
# gem 'sqlite3'

# new rubyserver
gem 'puma', '~> 3.4'

gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'exception_handler', '~> 0.5.0'
# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'pry-rails', '~> 0.3.4'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end


gem 'spree', '~> 3.1.0'
gem 'spree_gateway', '~> 3.1.0'
gem 'spree_auth_devise', '~> 3.1.0'
gem 'spree_i18n', git: 'git://github.com/spree/spree_i18n.git', branch: '3-1-stable'

#Heroku
gem 'rails_12factor', group: :production

# Custom extensions
gem 'spree_simple_sales', github: 'mPanasiewicz/spree_simple_sales', branch: 'master'
gem 'spree_related_products', github: 'spree-contrib/spree_related_products', branch: '3-1-stable'
gem 'spree_braintree_vzero', github: 'spree-contrib/spree_braintree_vzero', branch: '3-1-stable'
# gem 'spree_simple_sales', path: '../spree_simple_sales'
