# Step by Step Set up Jekyll website from scratch

## Setup

Env:
- Ruby
- RubyGems

ref: https://jekyllrb.com/docs/installation/macos/

### Build

- `jekyll build` - Builds the site and outputs a static site to a directory called `_site`.
- `jekyll serve` - Does the same thing except it rebuilds any time you make a change and runs a local web server at `http://localhost:4000`.
- `bundle exec jekyll serve --livereload --incremental` watch file