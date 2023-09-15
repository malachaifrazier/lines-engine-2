source "https://rubygems.org"

# Declare your gem's dependencies in lines.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'

#gem 'friendly_id', github: 'norman/friendly_id'
#gem 'meta-tags', require: 'meta_tags'
#gem 'rack-ssl-enforcer', require: 'rack/ssl-enforcer'
#gem 'acts-as-taggable-on', '~> 3.5.0'


group :development do
  gem 'capistrano'
  gem 'yard'
  gem 'autoprefixer-rails'
end

group :development, :test do
  gem 'rspec-rails', '~> 6.0.3'
  gem 'factory_girl_rails', require: false
  gem 'railroady'
  gem 'thor'
  gem 'pry'
end

group :test do
  gem 'faker'
  gem 'capybara'
  gem 'shoulda-matchers'
  gem 'guard-rspec', '= 4.7.3'
  gem 'rb-inotify', '~> 0.10.1'
  gem 'launchy'
end
