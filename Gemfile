source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
# gem "jekyll", "~> 3.7.0"

gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
    gem "jekyll-feed"
    gem "jekyll-scholar"
    gem "jekyll-paginate"
    gem "jekyll-sitemap"
    gem "jekyll-mentions"
end

group :development, :test do
  gem 'unicode_utils', require: false unless RUBY_VERSION >= '2.4'
end