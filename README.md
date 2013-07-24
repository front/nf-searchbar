#nf-searchbar

A jQuery customizable search bar.

**Example html:**

```
<form class="nf-searchbar" action="." method="get">
    <input type="text" name="q" placeholder="Enter search here...">
    <input type="submit" value="">
    <span class="nf-search-cancel"></span>
</form>
...
<a class="showBar">Search</a>
```

### nfSearchBar

```
$('a.showBar').searchBar('.nf-searchbar');
```

### Styling

This plugin uses the `nf-searchbar` class for styling the form and includes 2 css files.

 * `layout.css` - the layout for the form: position and dimensions.
 * `theme.css` - theming attributes: colors and fonts.

## Demo

[http://front.github.io/nf-searchbar/](http://front.github.io/nf-searchbar/)

## License

[MIT](https://github.com/front/nf-searchbox/blob/master/LICENSE)
