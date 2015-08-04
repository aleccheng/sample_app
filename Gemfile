source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
#As Hartl suggests, use the ruby sqlite3 gem instead.
gem 'sqlite3-ruby', '1.3.1', :require => 'sqlite3'
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

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  # Add gem Sqlite3 to :test because Heroku refuses to accept gem Sqlite3 in development
  #gem 'sqlite3'

  #gem 'rspec-rails', '~>2.0.1'
  gem 'rspec-rails', '~>3.3.0'

  #Suggested online add test-unit gem
  gem 'test-unit'

  #Try newer version
  gem 'rspec', '3.3.0'

  #Suggested to include this gem for rspec issues
  gem 'capybara'

end

#Add gem for sample_app
#group :development do
  #gem 'rspec-rails',  '2.0.1'
#end

#Add gem for sample_app (2 of 2)
group :test do
  gem 'webrat', '0.7.1'
  gem 'spork', '0.8.4'
end

