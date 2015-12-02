```css
@scope aside {
    p { 
        color: red; 
    }
}

/* Even though the rule below is more specific and declared later, 
   the previous selector is scoped, therefore it cannot be overriden. */

aside#sidebar p {  
    color: black; 
}
```

<br />
<small>Defined as part of the [W3C CSS Selectors Level 4 (working draft) specification](http://www.w3.org/TR/css-scoping-1/#at-ruledef-scope)</small>