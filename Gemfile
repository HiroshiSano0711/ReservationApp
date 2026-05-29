source "https://rubygems.org"

# アプリケーション本体（フレームワーク）
gem "rails", "~> 8.0.4", ">= 8.0.4.1"

# DB
gem "pg", "~> 1.1"

# Webサーバ
gem "puma", ">= 5.0"


# Windows用
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
end
