source "https://rubygems.org"

gem "jekyll", "~> 4.2.2"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.7"

gem "jekyll-sitemap", "~> 1.4"
gem "kramdown", "~> 2.4"
gem "liquid-c", "~> 4.0"

gem 'jekyll-zopfli', '~> 2.5'
gem 'jekyll-brotli', '~> 2.3'

gem 'nokogiri', '~> 1.12', '>= 1.12.4'
gem 'fastimage', '~> 2.2', '>= 2.2.5'

# load the featherweight theme
gem "featherweight"