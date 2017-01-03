## normalize-jss

JSS port of normalize.css. Inspired by:
https://github.com/necolas/normalize.css

#### Usage

```````````````````js
import jss from 'jss'
import normalize from 'jss-normalize'

jss.createStyleSheet(normalize, {named: false}).attach()
```````````````````

#### You must know

1. Dropped support of IE9. So, removed from original normalize CSS rules, writtend specially for IE9
2. Required jss plugins for correct working:
   1. **jss-vendor-preifxer**
   2. **jss-camelcase**

Anyway, you can use a [preset](https://github.com/cssinjs/jss-preset-default) for a quick setup with default plugins.

### License

MIT
