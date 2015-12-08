# Middleman Boilerplate

## About Middleman

Middleman is a static site generator built in Ruby. This makes it a great fit
for projects that may end up as a Ruby on Rails app. Its minimalistic structure
makes it very easy to work with, and includes support for deploying to Github
Pages.

## Includes

* [Sass](http://sass-lang.com):
  CSS with superpowers
* [Bourbon](http://bourbon.io):
  Sass mixin library
* [Neat](http://neat.bourbon.io):
  Semantic grid for Sass and Bourbon
* [Middleman Live Reload](https://github.com/middleman/middleman-livereload):
  Reloads the page when files change

##Installation
1. Download/clone to: `~/.middleman/middlemanbp`
2. Create your new Middleman project: `middleman init my_new_project --template=middlemanbp`

*Note: You can name the template whatever you like, so long as you call the same name in the `middleman init` command*

Run the server
```
middleman
```

## Directories

Stylesheets, fonts, images, and JavaScript files go in the `/source/assets/` directory.
