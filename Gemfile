source 'https://rubygems.org'

ruby '2.3.1'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.2'

gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'capybara', '~> 2.14'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'bcrypt', '~> 3.1', '>= 3.1.11'
gem 'factory_girl_rails', '~> 4.8'
gem 'faker', '~> 1.7', '>= 1.7.3'
gem 'will_paginate', '~> 3.1', '>= 3.1.5'
gem 'bootstrap-will_paginate', '~> 1.0'


group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
