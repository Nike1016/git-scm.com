# frozen_string_literal: true

source "https://rubygems.org"
ruby "2.4.2"

gem "rails", "~> 4.2.11", ">= 4.2.11.2"

gem "asciidoctor", ">=1.5.4"
gem "elasticsearch", "2.0.2"
gem "faraday"
gem "faraday_middleware"
gem "iso8601"
gem "octokit"
gem "puma"
gem "tilt"

gem "diff-lcs"
gem "json"
gem "launchy"
gem "netrc"
gem "nokogiri", ">= 1.16.5"
gem "redcarpet"
gem "yajl-ruby"

# Assets
gem "compass-rails", ">= 4.0.0"
gem "sass-rails", ">= 5.0.8"
gem "uglifier", "3.2.0"

group :development do
  gem "awesome_print"
  gem "better_errors"
  gem "binding_of_caller"
  gem "foreman"
end

group :development, :test do
  gem "bullet"
  gem "dotenv-rails", ">= 2.2.2"
  gem "pry-byebug"
  gem "rubocop-github"
  gem "ruby-prof"
  gem "sqlite3"
end

group :test do
  gem "database_cleaner"
  gem "fabrication"
  gem "rails-perftest"
  gem "rspec-rails", ">= 3.8.0"
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
