source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Api gems ######################################
gem 'active_model_serializers'
gem 'annotate'
gem 'cancancan'
gem 'carrierwave'
gem 'chronic'
gem 'devise'
gem 'exception_notification'
gem 'figaro'
gem 'hirb'
gem 'letter_opener', group: :development
gem 'paranoia'
gem 'pry-rails', group: :development
gem 'rails_admin'
gem 'rolify'

gem 'newrelic_rpm'
gem 'postmark-rails'

# gem 'ahoy_matey'
gem 'chartkick'
gem 'devise-async'
gem 'searchkick'

gem 'airborne'
gem 'httparty'

gem 'le'
########################################

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  # My Gems
  gem 'capybara'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'simplecov', '~> 0.7.1'
  gem 'spring-commands-rspec'
  # gem 'rack-mini-profiler'
  gem 'launchy'
  gem 'selenium-webdriver', '2.44.0'
  gem 'shoulda-matchers', require: false
  # gem "headless"
end

group :development do
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
