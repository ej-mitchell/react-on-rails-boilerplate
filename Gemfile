source 'https://rubygems.org/'

gem 'rails'
gem 'pg'
gem 'puma'
gem 'sass-rails'
gem 'uglifier'
gem 'jquery-rails'
gem 'webpacker'

group :development do
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :development, :test do
  gem 'capybara' #20190409: be careful with this one with macOS Mojave!!
  gem 'factory_bot_rails'
  gem 'launchy', require: false
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'shoulda'
  gem 'valid_attribute'
end

group :production do
  gem 'rails_12factor'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
