source "https://rubygems.org"

# Main Jekyll dependency
gem "jekyll", "~> 4.3.3"

# Theme and plugins
gem "minima", "~> 2.5"
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Required dependencies for Ruby 3.3.6
gem 'csv'
gem 'base64'
gem 'safe_yaml', '~> 1.0.5'
gem 'webrick', '~> 1.8' # Required for Ruby 3+

# Platform-specific dependencies
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
