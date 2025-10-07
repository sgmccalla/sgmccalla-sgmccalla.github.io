source "https://rubygems.org"

# Ensure compatibility with GitHub Actions and local Ruby installs
ruby ">= 3.2", "< 3.4"

# Core Jekyll engine
gem "jekyll", "~> 4.3"

# Theme (via remote_theme in _config.yml)
# You do NOT need to install minimal-mistakes-jekyll locally unless you vendor the theme.
# gem "minimal-mistakes-jekyll", "~> 4.24"

group :jekyll_plugins do
  gem "jekyll-scholar"       # for publications from BibTeX
  gem "jekyll-paginate"      # pagination for blog/index
  gem "jekyll-sitemap"       # automatic sitemap.xml
  gem "jekyll-feed"          # RSS feed
  gem "jemoji"               # GitHub-style emojis
  gem "jekyll-include-cache" # recommended by Minimal Mistakes for performance
end

# Needed for serving locally with Ruby 3+
gem "webrick", "~> 1.8"
