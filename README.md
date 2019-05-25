# Step by Step Set up Jekyll website from scratch

## Setup

Env:
- Ruby
- RubyGems

ref: https://jekyllrb.com/docs/installation/macos/

```
mkdir jekyll-website && cd jekyll-website
```

Create new `Gemfile`

```
bundle init
```

Now edit the `Gemfile` and add jekyll as a dependency:

```
gem "jekyll"
```

Finally run `bundle` to install jekyll for your project.


## Create a site

Create `index.html` in the root with the following content:

 ```
 <!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Home</title>
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html>
 ```

 ### Build

- `jekyll build` - Builds the site and outputs a static site to a directory called `_site`.
- `jekyll serve` - Does the same thing except it rebuilds any time you make a change and runs a local web server at `http://localhost:4000`.
- `bundle exec jekyll serve --livereload --incremental` watch file
