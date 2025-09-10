# unfamiliarplaces.net

Unfamiliar Places is a journal of the travels of Andrew and Dani.

## Development

The Unfamiliar Places blog is built with [Jekyll](https://jekyllrb.com/). To run it [Ruby](https://www.ruby-lang.org/) 3.2.0 is required.

Installation:
```
bundle install
```

Running:
```
bundle exec jekyll serve
```

To run with draft posts and published posts:
```
bundle exec jekyll serve --drafts
```

## Theme

The theme used is [Start Bootstrap - Clean Blog Jekyll](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll). 

Note: There is a [a fork](https://github.com/Gorlenah/startbootstrap-clean-blog-jekyll) that fixes a deprecation warning in Dart Sass.

The theme and HTML content use [Bootstrap](https://getbootstrap.com/).

The icons are provided by [Font Awesome](https://fontawesome.com/icons).

## Resizing images

Images are resized using [ImageMagick](https://imagemagick.org/index.php).

To resize an image to a maximum width of 1920px:
```
mogrify -resize 1920 *.jpg *.JPG
```