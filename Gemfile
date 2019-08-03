source 'https://rubygems.org'

# Specify your gem's dependencies in traject.gemspec
gemspec

group :development do
  gem "webmock", "~> 3.4"
end

group :debug do
  gem "ruby-debug", :platform => "jruby"
  gem "byebug", :platform => "mri"
end

gem 'sorbet', :group => :development
gem 'sorbet-runtime'
gem 'sorbet-rails'
gem 'redis' # for sorbet and cache_store
gem 'dalli' # for sorbet and cache_store
