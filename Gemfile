source 'https://rubygems.org'

ruby '2.2.3'

gem 'rack-fiber_pool', '~> 0.9.3',  :require => 'rack/fiber_pool'

gem 'grape', '~> 0.13.0'
gem 'grape-swagger', '~> 0.10.2'
gem 'grape-activerecord', '~> 1.1', '>= 1.1.2'

gem 'rake', '~> 10.4', '>= 10.4.2'


gem 'pry', '~> 0.10.3'
gem 'awesome_print', '~> 1.6', '>= 1.6.1'


group :development do
  gem 'sqlite3'
end

group :production do
  gem 'pg', '0.18.1'
  gem 'rails_12factor'
end