source 'https://rubygems.org'

# Specify your gem's dependencies in metasploit-erd.gemspec
gemspec

group :development, :test do
  # blank?
  # restrict for compatibility with rest of metasploit ecosystem until it upgrades to Rails 4
  gem 'activesupport', '>= 3.2', '< 4.0.0'
end

group :test do
    # Upload coverage reports to coveralls.io
  gem 'coveralls', require: false
  # code coverage of tests
  gem 'simplecov', :require => false
end
