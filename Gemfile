source 'https://rubygems.org'

# Read the current github-pages version straight from github
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
