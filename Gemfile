# Specify the source for Ruby gems
source "https://rubygems.org"

# Core Jekyll dependency with specific version to prevent any conflicts
gem "jekyll", "~> 4.3.2"

# Required for Jekyll to run on Ruby 3+ (handles HTTP server functionality)
gem "webrick", "~> 1.8"

# Remove GitHub Pages specific dependency which may be causing conflicts
# gem "github-pages", group: :jekyll_plugins

# Jekyll plugins for enhanced functionality
group :jekyll_plugins do
  # Generates RSS/Atom feed for blog posts
  gem "jekyll-feed"
  
  # Adds SEO meta tags for better search engine optimization
  gem "jekyll-seo-tag"
  
  # Generates a sitemap.xml for search engines
  gem "jekyll-sitemap"
end

# Specifically set kramdown parser to ensure compatibility
gem "kramdown", "~> 2.4.0"
gem "kramdown-parser-gfm", "~> 1.1.0"
gem "rouge", "~> 4.1.0"
