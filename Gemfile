source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.0"

gem "rails", "~> 7.0.2", ">= 7.0.2.3"
gem "sprockets-rails"
gem "pg"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

gem "figaro"
gem "devise"
gem "haml"
gem "simple_form"
gem "haml-rails", "~> 2.0"


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "pry"
  gem "pry-rails"
  gem "awesome_print"
  gem "rspec-rails"
end

group :development do
  gem "web-console"
  gem "listen", "~> 3.0"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "mailcatcher"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
