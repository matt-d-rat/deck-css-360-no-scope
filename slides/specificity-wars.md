##  Specificity wars

```html
<div class="foo bar"></div>
```

```css
/* The background color will be red */

.foo.bar {
    background-color: red;
}

.foo {
    background-color: blue;
}

.bar {
    background-color: green;
}
```

<aside class="notes">
    <ul>
        <li>More specific selectors will win.</li>
        <li>Background colour will be red.</li>
    </ul>
</aside>