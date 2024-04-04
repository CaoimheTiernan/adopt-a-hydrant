source 'https://rubygems.org'
ruby '2.3.1'

gem 'rails', '~> 7.0.8', '>= 7.0.8.1'

gem 'arel'
gem 'devise', '>= 4.7.0'
gem 'geokit'
gem 'haml'
gem 'http_accept_language'
gem 'nokogiri', '>= 1.15.6'
gem 'pg'
gem 'rails_12factor'
gem 'rails_admin', '>= 3.0.0'
gem 'validates_formatting_of'

platforms :ruby_18 do
  gem 'fastercsv'
end

group :assets do
  gem 'sass-rails', '>= 5.0.8'
  gem 'uglifier'
end

group :development do
  gem 'spring'
end

group :production do
  gem 'puma'
  gem 'skylight'
end

group :test do
  gem 'coveralls', require: false
  gem 'rubocop'
  gem 'simplecov', require: false
  gem 'sqlite3'
  gem 'webmock'
end
