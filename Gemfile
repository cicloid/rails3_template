source "http://rubygems.org"

gem "rails", "3.0.3"
gem "mysql2" # , :git => "git://github.com/brianmario/mysql2.git"
gem "state_machine"
gem "haml-rails", ">= 0.2"
gem "inherited_resources", ">=1.1.2"
gem "will_paginate", ">=3.0.pre2"
gem "simple_form" # , :git => "http://github.com/plataformatec/simple_form.git"
gem "devise", ">=1.1.2"
gem "cancan"
gem "formtastic", ">=1.1.0"
gem "friendly_id", "~>3.0"
gem "compass", ">= 0.10.5"
gem "lemonade", "0.3.4"
gem "barista", ">= 0.5.0"
gem "hoptoad_notifier", ">=2.3.6"
gem "cells"
gem "apotomo", "~> 1.0"
gem "simple_form"
gem "tabs_on_rails"
gem "dalli"
gem "twitter_oauth"
gem "carrierwave"
gem "conversational", :git => "git://github.com/cicloid/conversational.git"
gem "rest-client"
gem "twitter-text"


group :development do
  gem "autotest"
  gem "yaml_db", :require => false
  gem "autotest-notification"
  gem "rails3-generators", :git => "git://github.com/indirect/rails3-generators.git"
  gem "metric_fu", ">=1.5.1"
  gem "escape_utils", :require => false
  gem "rails-erd", :require => false
  gem "factory_girl_rails", :require => false
  gem "ffaker", :require => false
  gem "crewait", :require => false
  gem "livereload", :require => false
end

group :development, :test do
  gem "evergreen"
  gem "factory_girl_rails"
  gem "rspec-rails", ">=2.0.1"
  gem "evergreen", :require => "evergreen/rails"
  platforms :mri_18 do
    gem "ruby-debug"
  end
  platforms :mri_19 do
    gem "ruby-debug19", :require => "ruby-debug"
  end
end

group :test do
  gem "rspec", ">=2.0.1"
  gem "remarkable", ">=4.0.0.alpha4"
  gem "remarkable_activemodel", ">=4.0.0.alpha4"
  gem "remarkable_activerecord", ">=4.0.0.alpha4"
  gem "capybara-envjs"
end

group :cucumber do
  gem "cucumber", ">=0.6.3"
  gem "cucumber-rails", ">=0.3.2"
  gem "capybara", ">=0.3.6"
  gem "database_cleaner", ">=0.5.0"
  gem "spork", ">=0.8.4"
  gem "pickle", ">=0.4.2"
end

group :production do
  gem "newrelic_rpm", ">=2.12.3"
  gem "pg"
end

group :console do
  gem "map_by_method", :require => false
  gem "what_methods", :require => false
  gem "wirble", :require => false
  gem "net-http-spy"
  gem "hirb", :require => false
  gem "looksee", :require => false
  gem "sketches", :require => false
  gem "awesome_print", :require => false
  gem "interactive_editor"
end