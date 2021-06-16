# frozen_string_literal: true

source 'https://rubygems.org'
gemspec

# Temporarily pin jekyll to avoid absolute_url bug in 4.2
gem 'jekyll', '4.1'

# Windows patches
platforms :mswin, :mingw, :x64_mingw, :jruby do
  gem 'wdm', '>= 0.1.0' if Gem.win_platform?
  gem 'tzinfo-data'
end
