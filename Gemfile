source 'https://rubygems.org'
ruby '2.3.1'

gem 'rails', '~> 6.1.7', '>= 6.1.7.3'

gem 'arel'
gem 'devise', '>= 4.7.1'
gem 'geokit'
gem 'haml', '>= 5.0.0'
gem 'http_accept_language'
gem 'nokogiri', '>= 1.13.9'
gem 'pg'
gem 'rails_12factor'
gem 'rails_admin', '>= 2.0.0'
gem 'validates_formatting_of'

platforms :ruby_18 do
  gem 'fastercsv'
end

group :assets do
  gem 'sass-rails', '>= 6.0.0'
  gem 'uglifier'
end

group :development do
  gem 'spring'
end

group :production do
  gem 'puma', '>= 4.3.12'
  gem 'skylight'
end

group :test do
  gem 'coveralls', require: false
  gem 'rubocop', '>= 0.49.0'
  gem 'simplecov', require: false
  gem 'sqlite3'
  gem 'webmock'
end
