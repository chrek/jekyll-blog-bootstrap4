# jekyll-blog-bootstrap4

Jekyll Blog Site with Bootstrap 4 and Sass
------------------------------------------

This site is using jekyll and Bootstrap with Sass.

Bootstrap is installed from the source files and the scss directory copied to _sass/css/bootstrap of the site.

BootstrapCDN is also used to deliver cached version of Bootstrap’s compiled CSS and JS with CDN versions of jQuery and Popper.js.

## What has been implemented
* Cutomized Sass
* Navigation
* Pagination

## Testing locally

To test the site locally:

From the root of project run the commands:

1. `make build`
2. `make serve`

The site is using a Gemfile, so command like jekyll serve with bundle exec prefixed is appropriate:

`bundle exec jekyll serve`

<hr>

## References

1. [simpleit.rocks](https://simpleit.rocks/ruby/jekyll/tutorials/how-to-add-bootstrap-4-to-jekyll-the-right-way/).

2. [jekyllrb](https://jekyllrb.com/docs/pagination/)