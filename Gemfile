source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.0'

gem 'rails',                    '~> 5.2.3'
gem 'bcrypt',                   '~> 3.1', '>= 3.1.12'
gem 'faker',                    '~> 1.6', '>= 1.6.3'
gem 'carrierwave',              '~> 1.3', '>= 1.3.1'
gem 'mini_magick',              '~> 4.9', '>= 4.9.3'
gem 'will_paginate',            '~> 3.1'
gem 'bootstrap-will_paginate',  '~> 1.0'
gem 'bootstrap-sass',           '~> 3.4', '>= 3.4.1'
gem 'puma',                     '~> 3.11'
gem 'sass-rails',               '~> 5.0'
gem 'uglifier',                 '>= 1.3.0'
gem 'coffee-rails',             '~> 4.2'
gem 'jquery-rails',             '~> 4.3', '>= 4.3.3'
gem 'turbolinks',               '~> 5'
gem 'jbuilder',                 '~> 2.5'

group :development, :test do
  gem 'sqlite3',  '~> 1.3', '>= 1.3.11'
  gem 'byebug',   '~> 11.0', '>= 11.0.1', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console',            '>= 3.3.0'
  gem 'listen',                 '>= 3.0.5', '< 3.2'
  gem 'spring',                 '~> 2.0', '>= 2.0.2'
  gem 'spring-watcher-listen',  '~> 2.0.0'
end

group :test do
  gem 'rails-controller-testing', '~> 1.0', '>= 1.0.4'
  gem 'minitest',                 '~> 5.11', '>= 5.11.3'
  gem 'minitest-reporters',       '~> 1.3', '>= 1.3.6'
  gem 'guard',                    '~> 2.15'
  gem 'guard-minitest',           '~> 2.4', '>= 2.4.6'
end

group :production do
  gem 'pg',   '~> 1.1', '>= 1.1.4'
  gem 'fog',  '~> 2.1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
