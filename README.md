To build the site locally:

`bundle install`

`bundle exec jekyll -w --livereload`

Or with docker:

docker run -it --rm -v "$PWD":/usr/src/app -p "4000:4000" starefossen/github-pages

