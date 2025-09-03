source "https://rubygems.org"

gem "rails", "~> 8.0.2"
gem "cssbundling-rails",          "~> 1.4"                                     # CSS bundling
gem "jsbundling-rails",           "~> 1.3"                                     # JavaScript bundling
gem "madmin",                     "~> 2.1"
gem "pg",                         "~> 1.6.2"                                   # ActiveRecord PostgreSQL adaptor
gem "propshaft",                  "~> 1.1"                                     # Asset pipeline
gem "puma",                       "~> 6.0" # App server
gem "rubocop",                    "~> 1.79", require: false
gem "sidekiq",                    "~> 5.2.10" # Sidekiq/Redis background jobs
gem "stimulus-rails",             "~> 1.3"                                     # Stimulus JavaScript framework
gem "turbo-rails",                "~> 2.0"                                     # Turbo for modern web applications

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", "~> 1.18", require: false

# Required for Ruby 3+
gem "csv"
gem "mutex_m", "~> 0.3.0"
gem "observer"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

group :development do
  gem "foreman",                  "~> 0.87.2"                                  # Procfile execution
  gem "listen",                   ">= 3.1.5"
  gem "spring",                   "~> 4.0.0"                                   # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring-watcher-listen",    "~> 2.1.0"
  gem "web-console",              "~> 4.2"                                     # Access an interactive console on exception pages or by calling "console" anywhere in the code.
end
