source "http://rubygems.org"
git_source(:github) { |repo| "http://github.com/#{repo}.git" }

ruby "2.7.0"

gem "rails", "~> 6.0.2", ">= 6.0.2.1"

gem "puma", "~> 4.1"
gem "sass-rails", ">= 6"
gem "webpacker", "~> 4.0"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.7"
gem "bootstrap", "~> 4.4", ">= 4.4.1"
gem "bundler", "~> 2.1", ">= 2.1.4"
gem "bootsnap", ">= 1.4.2", require: false
gem "devise", "~> 4.7", ">= 4.7.1"

group :development do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "sqlite3", "~> 1.4"
end

group :production do
  gem "pg"
  gem "rails_12factor"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
