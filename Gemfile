source "https://rubygems.org"

# Use GitHub Pages, which includes Jekyll and other necessary plugins
gem "github-pages", group: :jekyll_plugins

# Optional: Include any plugins that GitHub Pages supports
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# If you're using the Minimal Mistakes theme via GitHub Pages, you don't need to include it here.
# Instead, use it as a remote theme in your _config.yml file:
# remote_theme: "mmistakes/minimal-mistakes@latest"

# Windows and JRuby platform-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows (optional)
# gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

gem 'jekyll-include-cache'