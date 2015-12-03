##  JavaScript Scope

```javascript
var topic = 'CSS';

// Code here cannot use the variable 'speaker'
// Code here can use the variable 'topic'

function presentation() {
    var speaker = 'Bob';

    // Code here can use the variable 'speaker'
    // Code here can use the variable 'topic'
}
```

<aside class="notes">
    <ul>
        <li>Lexical scope, or function Scoping</li>
    </ul>
</aside>