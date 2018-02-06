source 'http://rubygems.org'
ruby '2.3.1'

# If you update bundler here, make sure to update it in circle.yml too.
gem 'bundler', '~> 1.13.0'
gem 'rack', '~> 1.4.5'
gem 'rails', '~> 3.2.22.2'
gem 'railties', '~> 3.2.22'
gem 'unicorn', '~> 4.6.2'
gem 'execjs', '~> 1.4.0'
gem 'dotenv-rails', :groups => [:prod_staging, :production]
gem 'snappy', '= 0.0.15'
gem 'maxminddb', '~> 0.1.5'
gem 'doorkeeper'
gem "doorkeeper-mongodb"

gem 'test-unit'
gem 'parallel_tests'
gem 'verdict', '0.5'
gem 'multi_logger'

gem 'nunes'

# Killah Playa
gem 'unicorn-worker-killer'

# Content Autoloader dependencies
gem 'filewatcher'
gem 'colorize'

#### API
gem 'diff_match_patch', '~> 0.1.0'
gem 'json', '~> 1.8.3'
gem 'git', '~> 1.2.6'
gem 'grape', '~> 0.9.0'
gem 'grape-entity', '~> 0.4.4'
gem 'rack-cors', require: 'rack/cors'
gem 'rack-jsonp-middleware', '~> 0.0.8'
gem 'rack-timeout', '~> 0.0.3'
gem 'rake', '~> 10.1'
gem 'rest-client', '~> 1.8.0'
gem 'time-lord', '~> 0.2.5'
gem 'yajl-ruby', '~> 1.1.0'
gem 'statsd-ruby', '~> 1.2.0'
gem 'simple_segment'
gem 'statsd-instrument', '~> 1.7.2'
gem 'meta_events', '~> 1.0.1'
gem 'terminal', '~> 0.1.4'
gem 'hashie', '~> 2.1.2'
gem 'celluloid', '~> 0.16.0'
gem 'slack-notifier', '~> 1.1.0'
gem 'discourse_api', '~> 0.10.3'
gem 'parallel'
gem 'intercom', "~> 3.4.0"

gem "looker-sdk", git: 'https://github.com/looker/looker-sdk-ruby', ref: 'acc2acee91cf0891537343f0ed226042bc4c4f9e'

group :test do
  gem 'rb-fsevent', '~> 0.9.1'
  gem 'rspec'
  gem 'rspec-collection_matchers'
  gem 'rack-test'
  gem 'rspec-expectations', '~>3.4'
  gem 'rspec-mocks', '~> 3.4'
  gem "rspec_junit_formatter"
  gem 'webmock'
end
#### end api

# datastores
gem 'mongoid', '~> 3.1.6'
gem 'moped',   '= 1.5.3'

gem 'redis',            '~> 3.2.2'
gem 'redis-semaphore',  '~> 0.1.5'
gem 'redis-rails',      '~> 3.2.3'
gem 'redis-store',      '~> 1.1.3'
gem 'redis-rack-cache', '~> 1.2.1'
gem 'redis-objects',    '~> 0.9.1'

gem 'memcached', '~> 1.8.0'

# authentication / authorization
gem 'cancancan',              '~> 1.16.0'
gem 'devise',                 '=   3.5.4'
gem 'devise-token_authenticatable'
gem 'oauth',                  '= 0.4.7'
gem 'oauth2',                 '= 1.0.0'
gem 'omniauth',               '= 1.2.1'
gem 'omniauth-oauth2',        '= 1.2.0'
gem 'omniauth-facebook',      '= 4.0.0'
gem 'omniauth-twitter',       '= 0.0.14'
gem 'omniauth-google-oauth2', '= 0.1.13'
gem 'omniauth-github',        '= 1.1.2'

# projects
gem 'nokogiri',   '~>  1.7.2'

# misc
gem 'aws-sdk', '~> 2'
gem 'aws-sdk-v1'
gem 'clearbit',             '~> 0.2.7' # API to lookup company based on user's IP
gem 'excon',                '~> 0.27.5'
gem 'haml',                 '~> 3.1.7'
gem 'utf8-cleaner',         '~> 0.0.9'
# gem 'hashery',            '~> 2.1.0'
# exported to lib/hashery because of crappy gem config by rubyworks
gem 'http_accept_language', '~> 2.0.0'
gem 'jwt',                  '~> 1.5.4'  # oauth dependency
gem 'kaminari',             '~> 0.14.1' # pagination
gem 'will_paginate',        '~> 3.0.0'  # pagination
gem 'kiqstand',             '~> 1.0.0'  # sidekiq-mongo helper
gem 'kss',                  '~> 0.5.0'  # for styleguide
gem 'localeapp',            '~> 0.6.8'  # I18N-aaS
gem 'lograge',              '~> 0.1.0'  # nice logging
gem 'mail',                 '~> 2.5.5'
gem 'mini_magick',          '~> 3.6.0'
gem 'oj',                   '~> 1.4.4'  # fast JSON
gem 'octokit',              '~> 4.0'    # github
gem 'rack-contrib',         '~> 1.1.0'
gem 'rakismet',             '~> 1.3.0'
gem 'redcarpet',            '~> 3.3.4'  # markdown
gem 'sidekiq',              '~> 4.1.1'
gem 'whenever',             '~> 0.9.4' # crontab scheduling
gem 'sinatra',              '~> 1.3.6' # undeclared dependency of sidekiq/web
gem 'sinatra-contrib',      '~> 1.3.0'
gem 'slim',                 '~> 1.3.4' # undeclared dependency of sidekiq/web
gem 'split',                '~> 0.5.0' # ab testing magicks
gem 'tire',                 '~> 0.6.2'  # ElasticSearch DSL
gem 'tire-contrib',         '~> 0.1.3'
gem 'typhoeus',             '~> 0.6.3'  # HTTP requests
gem 'curb',                 '~> 0.8.5'
gem 'uri_template',         '~> 0.5.1'
gem 'useragent',            '~> 0.4.16' # Detect wooden browsers.
gem 'browser',              '~> 1.1.0'
gem 'referer-parser',       '~> 0.2.1'
gem 'murmurhash3',          '~> 0.1.3'
gem 'httparty',             '~> 0.11.0'
gem 'radix62',              '~> 1.0.1'
gem 'simple_form',          '~> 2.1.1'
gem 'sequel',               '~> 4.17.0'
gem 'pg',                   '~> 0.17.1'
gem 'recaptcha',            '~> 0.4.0', require: 'recaptcha/rails' # Detect auto-generated accounts
gem 'stripe',               '~> 1.57.1'
gem 'braintree',            '~> 2.57'
gem 'recurly',              '~> 2.11.2'
gem 'i18n-js',              '~> 3.0.2'
gem 'sass', 		            '= 3.2.9'
gem 'rollout',              '~> 2.3.0'
gem 'redis-namespace',      '~> 1.5.2'


# Debugging and performance measurement
gem 'newrelic_rpm', '~> 4.2.0.334'
gem 'newrelic-grape', '~> 2.0.0'

group :assets do
  gem 'sass-rails', '~> 3.2.5'
  gem 'autoprefixer-rails', '~> 5.1.9'
  gem 'uglifier',   '~> 2.7.2'
  gem 'r2',         '~> 0.2.2'
  gem 'turbo-sprockets-rails3'
end

group :development do
  gem 'pry-remote',        '~> 0.1.8'
  gem 'pry-stack_explorer','~> 0.4.9.2'
  gem 'pry-nav',           '~> 0.2.4', require: false
  gem 'brakeman',          '~> 3.1.4',  require: false
  gem 'cane',              '~> 2.5.0',  require: false
  gem 'foreman',           '~> 0.60.2', require: false
  gem 'haml-rails',        '~> 0.3.5'   # haml generators
  gem 'chef',              '~> 12.7.2'
  gem 'ffi-yajl',          '~> 2.2.0'
  gem 'capistrano',        '~> 2.15.4'
  gem 'capistrano-chef'
  gem 'capistrano-ext'
  gem 'capistrano-unicorn'
  gem 'meta_request',      '~> 0.2.6' # log parser for chrome dev tools
  gem 'capistrano-gitflow', '=1.4.3'
  gem 'spring', require: false
  gem 'spring-commands-rspec', require: false
end

group :test do
  gem 'capybara'
  gem 'database_cleaner', '~> 0.9.1'
  gem 'factory_girl',     '~> 4.2.0'
  gem 'launchy',          '~> 2.1.2'
  gem 'mongoid-rspec',    '~> 1.5.4'
  gem 'poltergeist'
  gem 'rspec-redis_helper'
  gem 'rspec-sidekiq'
  gem 'timecop'
end

group :development, :test do
  gem 'pry', '~> 0.9.10'
  gem 'quiet_assets',       '~> 1.0.1'
  gem 'rspec-rails',        '~> 3.4.2'
  gem 'selenium-webdriver',  '~> 3.6.0'
  gem 'msgpack',            '~> 0.5.8'
  gem 'ruby-jmeter',        '~> 2.11.3'
  gem 'rubocop',            '~> 0.29'
  gem 'fabrication',      '~> 2.16.1'
  gem 'childprocess'
  gem 'faker'
  gem 'stripe-ruby-mock', '~> 2.4.0', require: 'stripe_mock'
end
