source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.4", ">= 7.0.4.2"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use mysql as the database for Active Record
gem "mysql2", "~> 0.5"

group :development, :test do
  gem "planetscale_rails"
  #¥ N + 1問題を教えてくれる
  gem 'bullet'
end

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

gem "tailwindcss-rails", "~> 2.0"

gem "dartsass-rails", "~> 0.5.0"

gem "foreman"
gem "dockerfile-rails", ">= 1.5", :group => :development

gem "sentry-ruby", "~> 5.11"

gem "sentry-rails", "~> 5.11"

gem 'sassc'

# ERB Formatter/Beautify やたら不具合がおきるため、使用しない
# gem 'htmlbeautifier'

gem 'erb_lint', require: false

group :development, :test do
  gem 'rubocop', require: false
end

gem 'bcrypt'

#^ 青木 ★要更新 - 20231018 spa用
gem 'hotwire-rails'

# pagination
gem "kaminari"

gem "ransack"

# ¥ Format ERB https://tinyurl.com/yp8nffkn
# my devで vscode を開くと使えない... gemfileに入っているのに bundleしろと言われる
gem "erb-formatter"

# ruby formatter
gem "rufo"

# ! デバックツール 一度サーバーのrestartが必要 rails7だと対話シェルの入力が正しく行われないため使用しない
# 使い方 https://tinyurl.com/ylpt74du
gem 'pry-rails'

#! デバックツール 一度サーバーのrestartが必要 rails7だと対話シェルの入力が正しく行われないため使用しない
# group :development, :test do
#   gem 'byebug'
# end

#  ¥ binding_of_caller は動いてなさそう
# https://tinyurl.com/yse2cxy8
group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
end