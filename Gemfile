source 'https://rubygems.org'
ruby '2.3.1'

gem 'rails', '~> 4.2.8'

gem 'arel'
gem 'devise', '>= 4.2.1'
gem 'geokit'
gem 'haml'
gem 'http_accept_language'
gem 'nokogiri', '>= 1.16.5'
gem 'pg'
gem 'rails_12factor'
gem 'rails_admin', '>= 1.1.0'
gem 'validates_formatting_of'

platforms :ruby_18 do
  gem 'fastercsv'
end

group :assets do
  gem 'sass-rails', '>= 5.0.7'
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
