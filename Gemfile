source 'https://rubygems.org'

gem 'jruby-openssl', :platforms => :jruby
gem 'rake'
gem 'yard'

group :development do
  gem 'growl'
  gem 'kramdown'
  gem 'plymouth', :platforms => [:ruby_19, :ruby_20, :ruby_21]
  gem 'pry'
  gem 'pry-debugger', :platforms => [:mri_19, :mri_20]
  gem 'pry-byebug', :platforms => [:mri_21]
  gem 'rb-fsevent'
end

group :test do
  gem 'coveralls'
  gem 'json', '>= 1.8.1', :platforms => [:jruby, :ruby_18, :ruby_19]
  gem 'mime-types', '~> 1.25', :platforms => [:jruby, :ruby_18]
  gem 'rack-test'
  gem 'rest-client', '~> 1.6.0', :platforms => [:jruby, :ruby_18]
  gem 'rspec', '~> 3.0'
  gem 'rubocop', '>= 0.25', :platforms => [:ruby_19, :ruby_20, :ruby_21]
  gem 'simplecov', '>= 0.9'
end

gemspec
