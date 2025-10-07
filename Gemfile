# frozen_string_literal: true

source "https://rubygems.org"

gemspec

group :test, :development do
  gem "pry-byebug"
end

group :development do
  gem "rake"
  gem "rubocop", ">= 1.66.0"
  gem "rubocop-shopify", ">= 2.11.0"
  gem "rubocop-sorbet", ">= 0.7.0"
  gem "sorbet"
  gem "tapioca"
end

group :test do
  gem "minitest"
  gem "fakefs", require: false
  gem "webmock"
  gem "mocha"
end
