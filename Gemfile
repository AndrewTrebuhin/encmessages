source "https://rubygems.org"

ruby '2.3.0'

gem 'sinatra', '1.4.7'
gem 'data_mapper', '1.2.0'
gem 'attr_encrypted', '~> 3.0.0'

group :production do
  gem 'pg', '0.19.0'
  gem 'dm-postgres-adapter', '1.2.0'
end

group :development do
  gem 'dm-sqlite-adapter', '1.2.0'
end

group :test do
  gem 'rspec', '3.5.0'
  gem 'rack-test', '0.6.3'
end
