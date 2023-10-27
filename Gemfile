source 'https://gems.ruby-china.com/'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem "nokogiri", ">= 1.13.2"
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
gem 'activesupport', '>= 6.0.3.1'
gem "kramdown", ">= 2.3.0"
gem "rexml", ">= 3.2.5"
