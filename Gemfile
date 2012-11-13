source "https://rubygems.org"

gem "rails", "3.2.8"

gem "haml-rails"
gem "jquery-rails"


group :assets do
  gem "sass-rails",   "~> 3.2.3"
  gem "coffee-rails", "~> 3.2.1"
  gem "uglifier", ">= 1.0.3"
end

group :development, :test do
  gem "rspec-rails"
  gem "guard-rspec"
  gem "fabrication"

  # One day you won't have to download this manually
  # Download http://rubyforge.org/frs/download.php/75414/linecache19-0.5.13.gem
  # and run gem install ~/Downloads/linecach19-0.5.13.gem
  # Source: http://rubyforge.org/frs/?group_id=8883&release_id=46302
  gem "ruby-debug-base19x", "0.11.30.pre10"
  gem "ruby-debug-ide", "0.4.17.beta14"
  gem "linecache19", "0.5.13"
end

group :test do
  gem "mongoid-rspec"
end
