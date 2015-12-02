```html
<style>  
    p {
        color: black;
    }
</style>

<p>I will be coloured black.</p>

<section>  
    <style scoped>
        p {
            color: red;
        }
    </style>
    <p>I will coloured red because my styles are scoped!</p>
</section>

<p>I will also be coloured black.</p> 
```

<br />
<small>Defined as part of the [W3C CSS Selectors Level 4 (working draft) specification](http://www.w3.org/TR/selectors4/#scope-pseudo).</small>
