# frozen_string_literal: true

source "https://rubygems.org"

eval_gemfile "Gemfile.devtools"

gemspec

gem "dry-configurable"
gem "dry-logic"
gem "dry-types"

group :test do
  gem "dry-monads"
  gem "dry-struct"
  gem "i18n", "1.8.2", require: false
  gem "transproc"
  gem "json-schema"
end

group :tools do
  gem "pry"
  gem "pry-byebug", platform: :mri
  gem "redcarpet", platform: :mri
end

group :benchmarks do
  gem "actionpack", "~> 5.0"
  gem "activemodel", "~> 5.0"
  gem "benchmark-ips"
  gem "hotch", platform: :mri
  gem "virtus"
end
