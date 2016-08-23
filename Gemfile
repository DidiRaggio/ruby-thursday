source 'https://rubygems.org'

ruby '2.1.5'#'2.1.5p273'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7.1'

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

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
#RubySnack #4
gem 'devise'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

    group :development, :test do
        gem 'pry'
    gem 'pry-nav'
    gem 'pry-rails', '~> 0.3.2'
    gem 'rspec-rails'
        #other option comes with Rails -- gem 'byebug', platform: :mri
    end 

    group :development do
        gem 'better_errors'
    gem 'binding_of_caller'
        gem 'listen', '~> 3.0.5'
        gem 'letter_opener'
        gem 'spring'
        gem 'spring-watcher-listen', '~> 2.0.0'
    end

  group :test do
    gem 'capybara-email'
    gem 'capybara-webkit'
        gem 'database_cleaner'
    gem 'factory_girl_rails'
    gem 'faker' #some older RubySnacks reference 'ffaker'
    gem 'simple_bdd'
    gem 'shoulda-matchers'
  end 