source "https://rubygems.org"

group :jekyll_plugins do
	gem 'jekyll'
	gem 'github-pages'
	gem 'jekyll-feed'
	gem 'jekyll-scholar'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
gem "webrick", "~> 1.7"
