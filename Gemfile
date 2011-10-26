source 'http://rubygems.org'

gem 'rails', '~> 3.1.0'

gem 'sqlite3-ruby', :require => 'sqlite3'

# Use unicorn as the web server
gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'
gem 'capistrano-ext'
gem 'devise'
gem "configatron"
gem "post_commit"
gem "will_paginate"
gem "configatron"
gem "declarative_authorization"
gem "aasm"
gem "gravatar_image_tag"
gem "nifty-generators", :group => :development
gem "polish"
gem "ruby_parser"
gem "simple_form"
gem "i18n_generators"
gem "i18n_routing"
gem "kaminari"
gem "delayed_job"
gem "oauth2"
gem "fb_graph"
gem "omniauth"

group :development do
  # To use debugger
  gem 'ruby-debug'
  gem 'sqlite3-ruby', :require => "sqlite3"
  gem "nifty-generators"
end

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :test do
  gem 'webrat'
  gem 'rspec'
  gem 'rspec-rails'
end
gem "mocha", :group => :test