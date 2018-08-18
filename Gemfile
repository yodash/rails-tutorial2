source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

source 'https://rubygems.org'

gem 'rails',        '5.2.1'
gem 'puma',         '~> 3.11'
gem 'sass-rails',   '~> 5.0'
gem 'uglifier',     '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails', '4.3.1'
gem 'turbolinks',   '~> 5'
gem 'jbuilder',     '~> 2.5'
gem 'bootsnap', require: false

group :development, :test do
  gem 'sqlite3', '1.3.13'
  gem 'byebug',  '9.0.6', platform: :mri
end

group :development do
  gem 'web-console',           '>= 3.3.0'
  gem 'listen',                '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg', '1.0.0'
end