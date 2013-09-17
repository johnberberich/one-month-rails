source 'https://rubygems.org'

ruby '1.9.3'

gem 'rails', '4.0.0'

group :development, :test do
    gem 'sqlite3', group: [:development, :test]
    gem 'debugger'
end

group :production do
    gem 'pg', group: [:production]
end

gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 1.2'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end