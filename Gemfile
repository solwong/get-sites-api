ruby '2.3.1'

source 'https://rubygems.org'

# Environment via .env
gem 'dotenv-rails', '~> 2.1.1'

# Authorization
gem 'devise', '~> 4.2.0'
gem 'jwt', '~> 1.5.6'

gem 'mysql2', '~> 0.4.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.0.0.1'
# Use Puma as the app server
gem 'puma', '3.6.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  gem 'yard', '~> 0.9.2'
  gem 'factory_girl_rails', '~> 4.8.0'
  gem 'rspec-rails', '~> 3.5.2'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '9.0.6', platform: :mri
end

group :development do
  gem 'listen', '3.0.8'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '2.0.0'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'codecov', '~> 0.1.9', :require => false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
