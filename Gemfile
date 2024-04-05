# frozen_string_literal: true

source "https://rubygems.org"
ruby "3.1.3"

gem "rails", "~> 7.0", ">= 7.0.8.1"

# hacks for rails6 + ruby 3.1
gem 'net-imap', require: false
gem 'net-pop', require: false
gem 'net-smtp', require: false

gem "asciidoctor", "~> 2.0.0"
gem "elasticsearch", "2.0.2"
gem "iso8601"
gem "octokit"
gem "puma"

gem "diffy"
gem "nokogiri", ">= 1.15.6"
gem "rss"

# Assets
gem "sass-rails"
gem "uglifier"

group :development do
  gem "awesome_print"
  gem "better_errors", ">= 2.10.0"
  gem "binding_of_caller"
  gem "foreman"
end

group :development, :test do
  gem "dotenv-rails", ">= 2.8.0"
  gem "listen"
  gem "pry-byebug"
  gem "rubocop"
  gem "rubocop-discourse"
  gem "rubocop-performance"
  gem "rubocop-rails", ">= 2.17.0"
  gem "rubocop-rspec"
  gem "ruby-prof"
  gem "sqlite3"
end

group :test do
  gem "database_cleaner"
  gem "fabrication"
  gem "factory_bot_rails", ">= 6.3.0"
  gem "rails-controller-testing"
  gem "rspec-rails", ">= 5.0.3"
  gem "shoulda"
  gem "vcr"
  gem "webmock"
end

group :production do
  gem "pg"
  gem "rack-timeout"
  gem "rails_12factor"
  gem "redis-rails"
end
