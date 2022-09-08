source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

gem 'rails', '=7.0.3.1'


gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 5.6.5'
gem 'sass-rails', '~> 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.11'

gem 'bootsnap', '>= 1.4.2', require: false

gem 'bulma-rails', '~> 0.9.3'
gem 'bulma-extensions-rails', '~> 6.2.7'
gem 'devise', '=4.8.1'

gem 'omniauth', '= 2.1.0'
gem 'omniauth-facebook', '= 9.0.0'
gem 'faker', '=2.23.0'
gem 'kaminari'

gem 'stripe', '=7.1.0'
gem "figaro"
gem 'trestle', '~> 0.9.6'
gem 'trestle-auth', '=0.4.4'
gem 'trestle-search', '=0.4.3'
gem 'trestle-tinymce', '=0.3.1'
gem 'activemerchant', '=1.126.0'
gem "aws-sdk-s3", require: false



group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.2.0'
  gem 'listen', '>= 3.7.1', '< 3.8'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '=4.0.0'

end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.37.1'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
