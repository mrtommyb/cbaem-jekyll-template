# Chesapeake Bay Area Exoplanet Meeting website

This is a fork of an [existing template](https://github.com/CloudCannon/malt-jekyll-template) made by [CloudCannon](http://cloudcannon.com/). Browse through a [live demo](https://whispering-boat.cloudvent.net/).

## Develop

Malt was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~


## SEO Tag

This site uses the [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) plugin. You should at least set a title in front matter on each page. Have a look at the [project page](https://github.com/jekyll/jekyll-seo-tag) for more options.

## Google Analytics

[Google Analytics](https://www.google.com/analytics/) is a third party website analytics tool. To install:

1. Add your Google Analytics key to `_config.yml`.
2. Run your site in production `JEKYLL_ENV=production` (the default for CloudCannon and GitHub Pages).


## Image gallery / Featured

The image gallery is populated by a front matter array in `index.html`. To add items just copy the existing structure.
