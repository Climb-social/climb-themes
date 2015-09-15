# Climb Social - Themes
A collection of CSS themes for climb.social

## To embed a climb collection with a theme:
1. Insert css stylesheet of theme into head:
```html
<link rel="stylesheet" type="text/css" href="http://rawgit.com/Climb-social/climb-themes/master/themes/css/climb-red.css">
```
2. add the climb object to DOM, change data-collection attribute to you [collection id](http://app.climb.social/#collections/):
```html
<div class="climb-wall climb-red" data-collection="745475482">
</div>
```
3. add JS lib to end of body:
```html
<script src="//cdnjs.cloudflare.com/ajax/libs/mithril/0.2.0/mithril.min.js"></script>
<script type="text/javascript" src="https://rawgit.com/Climb-social/mithril-climb-wall/master/src/app.js"></script>
```

## To demo themes
1. see [Demo Page](http://rawgit.com/Climb-social/climb-themes/master/demo.html)
1. Or open in browser: `demo.html`


## To Write and compile scss files
1. ensure sass is installed: 'gem install sass'
1. enable watching/compiling 'sass --watch themes/sass:themes/css'
