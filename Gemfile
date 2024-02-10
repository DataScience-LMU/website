source "https://rubygems.org"

gem "jekyll", "=3.9.4"
gem "rack"
gem "webrick", "~> 1.7"
gem "kramdown-parser-gfm" # Add this line

group :jekyll_plugins do
  gem "jekyll-feed"
  gem 'jekyll-admin', "0.9.0"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", :install_if => Gem.win_platform?

