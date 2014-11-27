source 'https://rubygems.org'
ruby '2.1.2'
gem 'jekyll'
gem 'kramdown'
gem 'rake'

## Github Pages

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
