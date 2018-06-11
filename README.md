jekyll-theme-semantic
=====================

[![Build Status](https://travis-ci.org/rcvalle/jekyll-theme-semantic.svg?branch=master)](https://travis-ci.org/rcvalle/jekyll-theme-semantic)

A [Semantic UI](https://semantic-ui.com/) -based Jekyll theme.


Installation
------------

To install jekyll-theme-semantic:

1. Add the following line to your Jekyll site's `_config.yml` file:

       theme: jekyll-theme-semantic

2. Add the following line to your Jekyll site's `Gemfile` file:

       gem 'jekyll-theme-semantic'

3. On a command prompt or terminal with your Jekyll site's directory as the
   current working directory, run the following command:

       $ bundle install


Usage
-----

To use jekyll-theme-semantic:

1. Copy the `_plugins` directory from the theme's directory to your Jekyll
   site's directory.

2. Copy the `category.html` and `tag.html` files from the theme's `_layouts`
   directory to your Jekyll site's `_layouts` directory.

3. Copy the `index.html` file from the theme's directory to your Jekyll
   site's directory.

4. Add the following line to your Jekyll site's `_config.yml` file, replacing the number with the number of posts you would like to appear on each page:

       paginate: 5

5. Make sure `- jekyll-paginate` is listed in your Jekyll site's `_config.yml` file under `plugins`:

       plugins:
         - jekyll-feed
         - jekyll-paginate

6. Optional: Add the following line to your Jekyll site's `_config.yml` file
   and replace `UA-XXXXX-Y` by your Analytics tracking ID:

       analytics: UA-XXXXX-Y

7. Optional: Add the following line to your Jekyll site's `_config.yml` file
   and replace `EXAMPLE` by your Disqus shortname:

       disqus_shortname: EXAMPLE

To customize jekyll-theme-semantic, see [Overriding theme
defaults.](https://jekyllrb.com/docs/themes/#overriding-theme-defaults)


Contributing
------------

See [CONTRIBUTING.md](CONTRIBUTING.md).


License
-------

Licensed under the MIT license. See [LICENSE](LICENSE) for license text and
copyright information.
