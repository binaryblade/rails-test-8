source "https://rubygems.org"

ruby "3.4.1"

gem "rails", "~> 8.0.1"
gem "propshaft"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "thruster", require: false
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "tailwindcss-rails"
gem "jbuilder"
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"
gem "bootsnap", require: false
gem "kamal", require: false

gem "tzinfo-data", platforms: %i[ windows jruby ]

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
  gem "solargraph", "~> 0.51.2"
  gem "solargraph-rails", "~> 1.1"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end

