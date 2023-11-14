source "https://rubygems.org"

# Jekyll dan semua dependenciesnya dikelola oleh gem github-pages.
# Ini akan memastikan bahwa build lokal Anda akan meniru environment GitHub Pages.
gem "github-pages", group: :jekyll_plugins

# Jika Anda memiliki plugins Jekyll tambahan, masukkan mereka di sini.
group :jekyll_plugins do
  # Misalnya:
  # gem "jekyll-seo-tag"
  # Tapi pastikan plugin tersebut didukung oleh GitHub Pages.
end

# Platform-specific gems untuk Windows dan JRuby.
# Ini tidak perlu disesuaikan untuk GitHub Pages.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster untuk watching directories pada Windows.
# Tidak relevan untuk GitHub Pages, hanya untuk pengembangan lokal.
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Khusus JRuby, tidak relevan untuk GitHub Pages.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
