# frozen_string_literal: true

source "https://rubygems.org"

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

gem "jekyll", "~> 4.3"
gem "bundler", "~> 2.3"
gem "webrick" # Jekyll 本地运行所需

gem "jekyll-theme-chirpy"
