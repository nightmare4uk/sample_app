source 'https://rubygems.org'

gem 'rails'


group :test do
  gem 'selenium-webdriver' # Для capybara
  gem 'capybara' #Для симмуляции пользователя
  gem 'libnotify' # для лога guard
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do
  gem 'sqlite3'
  gem 'spork-rails', github: 'sporkrb/spork-rails'	
  gem 'childprocess'
  gem 'guard-spork'
  gem 'rspec-rails' #Сами тесты
  gem 'guard-rspec' #для автоматического тестирования
end

gem 'jquery-rails'

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
