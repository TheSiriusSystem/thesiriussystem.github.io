source "https://rubygems.org"

gem "github-pages"
gem "webrick", "~> 1.8.1"

# Website theme
gem "minima", "~> 2.5.1"

group :jekyll_plugins do
    gem "faraday-retry", ">= 2.2.1"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", "~> 2.0.6"
    gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]