# frozen_string_literal: true

source 'https://rubygems.org'

if ENV['RAILS_VERSION'] == 'edge'
  gem 'rails', git: 'https://github.com/rails/rails.git'
elsif ENV['RAILS_VERSION']
  gem 'rails', "~> #{ENV['RAILS_VERSION']}.0"
else
  gem 'rails'
end

gem 'sqlite3'

gem 'nokogiri', '>= 1.7'
gem 'loofah', '>= 2.20'

gem 'selenium-webdriver'
