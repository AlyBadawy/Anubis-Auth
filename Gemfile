source "https://rubygems.org"

gem "bcrypt", "~> 3.1.7"
gem "bootsnap", require: false # Reduces boot times through caching; required in config/boot.rb
gem "jbuilder"
gem "kamal", require: false
gem "puma", ">= 5.0"
gem "rack-cors"
gem "rails", "~> 8.0.2"
gem "solid_cable"
gem "solid_cache"
gem "solid_queue"
gem "sqlite3", ">= 2.1"
gem "thruster", require: false # Add HTTP asset caching/compression and X-Sendfile acceleration to Puma
gem "tzinfo-data", platforms: %i[ windows jruby ]

group :development do
  gem "rubocop"
  gem "rubocop-config-prettier"
  gem "rubocop-performance"
  gem "rubocop-rails"
  gem "rubocop-rails-omakase", require: false # Omakase Ruby styling [https://github.com/rails/rubocop-rails-omakase/]
  gem "rubocop-rspec"
end

group :test do
  gem "shoulda-matchers"
  gem "simplecov"
end

group :development, :test do
  gem "brakeman", require: false # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "capybara"
  gem "database_cleaner"
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "faker"
  gem "pry-byebug"
  gem "pry-rails"
  gem "rspec-rails"
end

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"
