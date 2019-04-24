source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.3.3"

gem "bcrypt", "~> 3.1.7"
gem "bootsnap", ">= 1.1.0", require: false
gem "capistrano-rails", group: :development
gem "jbuilder", "~> 2.5"
gem "mini_magick", "~> 4.8"
gem "mysql2", ">= 0.4.4", "< 0.6.0"
gem "puma", "~> 3.11"
gem "rails", "~> 5.2.1"
gem "sass-rails", "~> 5.0"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"
# gem 'coffee-rails', '~> 4.2'
# gem 'redis', '~> 4.0'

group :development, :test do
  gem "byebug", platforms: %i[mri mingw x64_mingw]
  gem "pry-rails"
  gem "rspec-rails", "~> 3.8"
  gem "rubocop"
  gem "rubocop-performance"
end

group :development do
  # may use web-console later
  # gem 'web-console', '>= 3.3.0'
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "chromedriver-helper"
  gem "selenium-webdriver"
end
