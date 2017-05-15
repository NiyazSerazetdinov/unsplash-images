source "https://rubygems.org"

ruby "2.3.1"

gem "pg"
gem "rails", "~> 5.0.1"

# server
gem "puma", "~> 3.0"

# CORS
gem "rack-attack"
gem "rack-cors"

# json
gem "active_model_serializers"

# main
gem "apitome"
gem "decent_exposure"
gem "listen", "~> 3.0.5"
gem "responders"
gem "rspec_api_documentation"
gem "unsplash"

group :development do
  gem "bullet"
  gem "spring"
  gem "spring-commands-rspec"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :development, :test do
  gem "brakeman"
  gem "bundler-audit"
  gem "byebug", platform: :mri
  gem "codeclimate-test-reporter", "< 1.0", require: false
  gem "database_cleaner"
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "faker"
  gem "json_spec"
  gem "rspec-rails"
  gem "rubocop", require: false
  gem "rubocop-rspec", require: false
  gem "shoulda-matchers", require: false
  gem "webmock", require: false
end
