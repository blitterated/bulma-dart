# Build Bulma with Sass CLI

[Original directions](https://bulma.io/documentation/customize/with-sass-cli/) suggest installing the Sass ruby gem and compiling with that. 

It's since [been deprecated](https://sass-lang.com/ruby-sass) in favor of [the Dart implementation](https://sass-lang.com/dart-sass) or [LibSass](https://sass-lang.com/libsass).

After installing, this document loosely follows the [original directions](https://bulma.io/documentation/customize/with-sass-cli/)

## Install Dart Sass
[Installation Instructions here](https://sass-lang.com/install), but on a mac it's as simple as:

    brew install sass/sass/sass

## Build bulma by itself

    sass --sourcemap=none sass/bulma-0.9.0/bulma.sass:css/bulma.css

## Build a bulma css file via @import

    sass --sourcemap=none sass/mystyles.scss:css/mystyles.css
