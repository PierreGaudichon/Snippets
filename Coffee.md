### Check the type
[Source](https://github.com/lodash/lodash/blob/2.4.1/dist/lodash.compat.js#L2724)

```coffee
  typeof o is "function"
```

### Apply, Call
[Call](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Function/call), [Apply](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Function/apply).

```coffee
  fun.apply @, [a, b]
  fun.call @, a, b
```

### Arguments as an array
[Source](https://shifteleven.com/articles/2007/06/28/array-like-objects-in-javascript/)
```coffee
args = Array.prototype.slice.call arguments
```

### Random hexadecimal color
[Source](http://www.paulirish.com/2009/random-hex-color-code-snippets/)
```coffee
'#'+Math.floor(Math.random()*16777215).toString(16)
```
