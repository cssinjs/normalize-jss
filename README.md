## normalize-jss

[JSS](https://github.com/cssinjs/jss) port of [normalize.css](https://github.com/necolas/normalize.css).

#### Usage

```````````````````js
import jss from 'jss'
import normalize from 'normalize-jss'

jss.createStyleSheet(normalize).attach()
```````````````````

#### You must know

Required jss plugins for correct working:
  1. [jss-vendor-prefixer](https://github.com/cssinjs/jss-vendor-prefixer)
  2. [jss-camel-case](https://github.com/cssinjs/jss-camel-case)
  3. [jss-global](https://github.com/cssinjs/jss-global)

Anyway, you can use a [preset](https://github.com/cssinjs/jss-preset-default) for a quick setup with default plugins.

### Issues

File a bug against [cssinjs/jss prefixed with \[normalize-jss\]](https://github.com/cssinjs/jss/issues/new?title=[normalize-jss]%20).

### License

MIT
