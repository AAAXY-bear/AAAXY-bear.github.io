source "https://rubygems.org"

gem "jekyll", "~> 4.3.0"
gem "minima", "~> 2.5"

# 如果使用 GitHub Pages，取消注释下面这行
# gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.7"
  gem "jekyll-sitemap", "~> 1.4"
end

# Windows 和 JRuby 兼容性
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1"
  gem "tzinfo-data"
end

# 性能优化
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "webrick", "~> 1.7"
