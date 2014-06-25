source "https://rubygems.org"

group :development, :test do
  gem 'rake'
  gem 'mongoid', '2.6.0'
  gem 'bson_ext', :platforms => :ruby
  gem 'geoip'
  gem 'rubyzip'
  gem 'rails'

  platforms :mri do
    gem 'debugger'
  end

  platforms :jruby do
    gem 'jruby-openssl'
    gem 'jgeoip'
  end
end

gemspec
