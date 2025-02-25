# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", "~> 4.4.1"
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
gem "webrick" # Required for Jekyll on Ruby 3.x

group :jekyll_plugins do
  gem "jekyll-scholar"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-feed"
  gem "jekyll-sass-converter", "~> 3.1.0"
end

gem "stringio", "~> 3.1.5" # Ensure compatibility

