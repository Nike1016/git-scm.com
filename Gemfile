# frozen_string_literal: true

source "https://rubygems.org"
ruby "2.4.2"

gem "rails", "~> 6.1.7", ">= 6.1.7.3"

gem "asciidoctor", ">= 1.5.8"
gem "elasticsearch", "2.0.2"
gem "faraday"
gem "faraday_middleware"
gem "iso8601"
gem "octokit"
gem "puma", ">= 4.3.12"
gem "tilt"

gem "diff-lcs"
gem "json", ">= 2.3.0"
gem "launchy"
gem "netrc"
gem "nokogiri", ">= 1.13.9"
gem "redcarpet", ">= 3.5.1"
gem "yajl-ruby", ">= 1.4.2"

# Assets
gem "compass-rails"
gem "sass-rails", ">= 6.0.0"
gem "uglifier", "3.2.0"

group :development do
  gem "awesome_print"
  gem "better_errors", ">= 2.8.0"
  gem "binding_of_caller"
  gem "foreman"
end

group :development, :test do
  gem "bullet"
  gem "dotenv-rails", ">= 2.7.6"
  gem "pry-byebug"
  gem "rubocop-github"
  gem "ruby-prof"
  gem "sqlite3"
end

group :test do
  gem "database_cleaner"
  gem "fabrication"
  gem "rails-perftest"
  gem "rspec-rails"
  gem "shoulda-matchers"
  gem "vcr"
  gem "webmock"
end

group :production do
  gem "pg", "0.21.0"
  gem "rack-timeout"
  gem "rails_12factor"
  gem "redis-rails"
end
