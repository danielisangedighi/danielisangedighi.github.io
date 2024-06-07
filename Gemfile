source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Add webrick for serving the site locally
gem "webrick", "~> 1.7"

# Add csv gem for compatibility with Ruby 3.4.0+
gem "csv"

# Add faraday-retry to handle retry middleware with Faraday v2.0+
gem "faraday-retry"

# Performance-booster for watching directories on Windows
# gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
