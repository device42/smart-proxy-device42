source 'https://rubygems.org'
gemspec

group :development do
  if RUBY_VERSION < '1.9.3'
    gem 'rake', '< 11'
  else
    gem 'rake'
    gem 'test-unit'
  end
  gem 'mocha'
  gem 'webmock'
  gem 'smart_proxy', :github => 'theforeman/smart-proxy', :branch => 'develop'
end
