source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.5.1"

gem "rails", "~> 6.0.3", ">= 6.0.3.3"
gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 5.3"
gem "bootsnap", ">= 1.4.2", require: false
gem "rack-cors", require: "rack/cors"
gem "active_model_serializers"
gem "devise_token_auth"
gem "stripe-rails"
gem 'aws-sdk-s3'

group :development, :test do
  gem "pry-byebug"
  gem "pry-rails"
  gem "rspec-rails"
  gem "shoulda-matchers"
  gem "factory_bot_rails"
  gem "coveralls", require: false
  gem "stripe-ruby-mock", "3.0.0"
end

group :development do
  gem "listen", "~> 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end
