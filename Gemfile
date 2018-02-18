# Gemfile
source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'jekyll'

group :jekyll_plugins do
  gem 'github-pages'
  gem 'jekyll-paginate-v2'
end
