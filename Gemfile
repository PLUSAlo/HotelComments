source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.6'

group :development do
	gem 'sqlite3', '~> 1.3', '>= 1.3.11'
end


gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails', '~> 4.0', '>= 4.0.3'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'



group :production do
	gem 'pg', '~> 0.18.4'
	gem 'rails_12factor', '~> 0.0.3'
end


group :development, :test do
   gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
   gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
