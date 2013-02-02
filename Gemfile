source 'https://rubygems.org'

ruby '1.9.3'

gem 'rails',        '3.2.11'
gem 'jquery-rails', '2.0.2'
gem 'thin',         '1.5.0'
gem 'bootstrap-sass', '2.2.2.0'

group :development do
  gem 'foreman'       # run 'foreman start' from command line to bootstrap app server
  gem 'heroku'        # useful commands to interact with Heroku
end

group :development, :test do
  gem 'sqlite3',      '1.3.5'
  gem 'rspec', :require => false
  gem 'rspec-rails',  '2.12.2'
end

group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier',     '1.2.3'
end

group :test do
  gem 'capybara', '1.1.2'
end

group :production do
  gem 'pg'
end
