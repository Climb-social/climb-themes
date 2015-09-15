# Climb Social - Themes
A collection of CSS themes for climb.social

## To embed a climb collection with a theme:
- Insert css stylesheet of theme into head:
```html
<link rel="stylesheet" type="text/css" href="http://rawgit.com/Climb-social/climb-themes/master/themes/css/climb-red.css">
```
- add the climb object to DOM, change data-collection attribute to you [collection id](http://app.climb.social/#collections/):
```html
<div class="climb-wall climb-red" data-collection="745475482">
</div>
```
- add JS lib to end of body:
```html
<script src="//cdnjs.cloudflare.com/ajax/libs/mithril/0.2.0/mithril.min.js"></script>
<script type="text/javascript" src="https://rawgit.com/Climb-social/mithril-climb-wall/master/src/app.js"></script>
```

## To demo themes
- see [Demo Page](http://rawgit.com/Climb-social/climb-themes/master/demo.html)
- Or open in browser: `demo.html`


## To Write and compile scss files
- ensure sass is installed: 'gem install sass'
- enable watching/compiling 'sass --watch themes/sass:themes/css'
