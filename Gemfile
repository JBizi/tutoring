source 'https://rubygems.org'
gem 'rails', '~> 4.2.0'
#gem 'devise'
gem 'sass-rails', '~> 5.0.1'
gem 'uglifier', '~> 2.5.3'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'bootstrap-sass', '~> 3.3.4.1'
#gem 'high_voltage'
group :therubyracer do
  gem 'therubyracer', :platform=>:ruby
end
group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  #em 'better_errors'
  #gem 'binding_of_caller', :platforms=>[:mri_19]
  #gem 'quiet_assets'
  #gem 'rails_layout'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'
  gem 'rails_log_stdout',	github: 'heroku/rails_log_stdout'
  gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
  gem 'unicorn'
end
