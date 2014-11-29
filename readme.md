## Vendor prefixer plugin for JSS

Vendor prefixes are handled automatically using a smart check which results are cached. [See example.](http://jsstyles.github.io/jss-vendor-prefixer/examples/property/index.html)

```javascript
{
    '.container': {
        transform: 'translateX(100px)'
    }
}
```
```css
.container {
    transform: -webkit-translateX(100px);
}
```

## Register plugin

```javascript
var jss = require('jss')
var extend = require('jss-extend')
jss.use(extend)
```

## Run tests

### Locally
```bash
npm i
open test/local.html
```
### From github

[Tests](https://jsstyles.github.com/jss-extend/test)

## License

MIT