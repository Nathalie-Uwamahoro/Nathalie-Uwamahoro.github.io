source "https://rubygems.org"

# Use the version of Jekyll that GitHub Pages supports
gem "github-pages", group: :jekyll_plugins

# Theme (Optional: Change to any theme you want)
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows compatibility fixes
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
