## normalize-jss

JSS port of normalize.css. Inspired by:
https://github.com/necolas/normalize.css

#### Usage

```````````````````js
import jss from 'jss'
import normalize from 'jss-normalize'

jss.createStyleSheet(normalize).attach()
```````````````````

#### You must know

Required jss plugins for correct working:
  1. **jss-vendor-preifxer**
  2. **jss-camelcase**
  3. **jss-global**

Anyway, you can use a [preset](https://github.com/cssinjs/jss-preset-default) for a quick setup with default plugins.

### License

MIT
