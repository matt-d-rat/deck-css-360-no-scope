When importing the CSS Module from a JS Module, it exports an object with all mappings from local names to global names.

<br />
__ES6 imports__
```javascript
import styles from './Nav.css';
element.innerHTML = '<div class="' + styles.container + '">';
```

<br />
__CommonJS imports__
```javascript
var styles = require('./Nav.css');
element.innerHTML = '<div class="' + styles.container + '">';
```