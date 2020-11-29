# frozen_string_literal: true

source 'https://rubygems.org'
gemspec

gem 'kramdown', '~> 2.3.0'

gem 'octokit', '~> 4.18'

gem 'rubocop', '~> 0.71'

# Octokit does not work with the most recent version of faraday so this locks it to a version that works.
gem 'faraday', '~> 0.17.1'

gem 'rake'

gem 'rdoc'

group :test do
  gem 'minitest'
  gem 'mocha'
  gem 'simplecov'
end
