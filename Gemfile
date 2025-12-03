
source "https://rubygems.org"

# ruby "3.3.4"

# Core Jekyll
gem "jekyll", "~> 4.3"

# Plugins (pure Ruby, no native extensions)
gem "jekyll-feed", "~> 0.17"
gem "jekyll-sitemap"
gem "jekyll-seo-tag"
gem "jekyll-tidy"
gem "kramdown-math-katex"

# Pure Ruby Sass converter
gem "jekyll-sass-converter", "~> 3.0"

# Required for Jekyll serve / Cloudflare Pages
gem "webrick"

# CSV support for Ruby 3.4+
gem "csv", "~> 3.3"

# Windows-specific support
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", install_if: Gem.win_platform?

