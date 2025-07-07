source "https://rubygems.org"

gem "rails", "~> 8.0.2"

gem "importmap-rails"
gem "jbuilder"
gem "pg", "~> 1.1"
gem "propshaft"
gem "puma", ">= 5.0"
gem "stimulus-rails"
gem "tailwindcss-rails"
gem "turbo-rails"

gem "tzinfo-data", platforms: %i[ windows jruby ]

gem "solid_cable"
gem "solid_cache"
gem "solid_queue"

gem "bootsnap", require: false
gem "kamal", require: false
gem "thruster", require: false

group :development, :test do
  gem "brakeman", require: false
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "guard", "~> 2.19"
  gem "guard-minitest", "~> 2.4"
  gem "minitest-reporters", "~> 1.7"
  gem "rubocop-rails-omakase", require: false
  gem "solargraph", "~> 0.56.0"
  gem "solargraph-rails", "~> 1.1"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
