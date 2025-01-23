# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

gem "jekyll", "~> 4.3.4"
gem "csv"
gem "logger"
gem "base64"
gem "webrick" # 如果运行 `jekyll serve` 时提示缺少 webrick，也需要添加