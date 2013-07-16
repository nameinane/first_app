source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.0'

group :development do
  gem 'sqlite3', '1.3.7'
end

gem 'sass-rails', '4.0.0'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.0'
gem 'jquery-rails', '2.2.1'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
#  gem 'pg', '0.15.1'
  # Warning, if you remove the version number and end up with postgres > 0.14, expect this:
  # #/app/vendor/bundle/ruby/2.0.0/gems/activerecord-3.2.13/lib/active_record/connection_adapters/postgresql_adapter.rb:1216:in `initialize': invalid connection option "fallback_application_name" (PG::Error)
  # when trying to get app running on Heroku
  gem 'pg', '=0.14.1'
  gem 'rails_12factor', '0.0.2'
end