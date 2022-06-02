source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.3"

gem "sprockets-rails"

gem "puma", "~> 5.0"

gem "importmap-rails"

gem "turbo-rails"

gem "stimulus-rails"

gem "jbuilder"

gem 'tzinfo'
gem "tzinfo-data"

gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do

  gem "debug", platforms: %i[ mri mingw x64_mingw ]

end

group :production do

  gem 'pg', '~> 1.3', '>= 1.3.5'

end

group :development do

  gem "web-console"
  gem "sqlite3", "~> 1.4"

end

