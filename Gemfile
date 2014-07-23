source 'https://rubygems.org'
ruby '1.9.3'
gem 'rails', '3.2.12'
gem 'google-api-client', '>= 0.6'
gem 'jquery-rails'
gem 'cancan'
gem 'devise', '2.2.4'
gem 'figaro'
gem 'libv8'
gem 'mongoid'
gem 'rolify'
gem 'simple_form'
gem 'jwt', '~> 0.1.4'
# gem 'sidekiq'
gem 'twitter', '4.8.1'
gem 'sexmachine' # get gender from firstname
gem 'rufus-scheduler', '2.0.22'
gem 'rails_12factor' # Heroku recommended to add this gem
gem 'lazy_high_charts' # needed for graphics
gem 'leaflet-rails', '0.6.4' # needed for the maps
gem 'bootstrap-datepicker-rails'
gem 'will_paginate'
gem 'classifier' # classifier
# Bayes Motel classifier
# gem 'bayes_motel'
# NBayes classifier https://github.com/oasic/nbayes
gem 'nbayes'
group :assets do
  gem 'less-rails'
  gem 'therubyracer', :platform=>:ruby, :require=>"v8"
  gem 'twitter-bootstrap-rails'
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'jquery-datatables-rails', github: 'rweng/jquery-datatables-rails'
  gem 'jquery-ui-rails'
end
group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :rbx]
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'pry-rails'
  gem 'awesome_print'
  # gem 'debugger' # needed for debug
  # gem 'ruby-debug-ide'
  # gem 'ruby-debug-base'
end
group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end
group :test do
  gem 'capybara'
  gem 'cucumber-rails', :require=>false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'launchy'
  gem 'mongoid-rspec'
  gem 'minitest'
end
