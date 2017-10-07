# R@M Website Documentation
##### Written by Omkar Konaraddi

## Jekyll
This website is using [Jekyll](https://jekyllrb.com/), a blog-aware static site generator. Jekyll allows the website to be broken into reusable components that can be used in multiple places and for templating in an efficient manner. 

Please read the Jekyll docs before reading any further.

### Building the site
Run `jekyll build` to build the site; the site is located in `_site/` at the root directory. Note that any edits you make inside `_site/` will be overridden in the build process (and no edits should be made in the `_site/`).

## CSS framework
This website is using [Bulma](http://bulma.io) 0.4.2, this is a CSS framework. Read up on Sass at [marksheet.io](http://marksheet.io/) and the [Sass docs](http://sass-lang.com/). If you add a Sass file to `_sass/`, don't forget to import that file in the `styles.scss` file too.