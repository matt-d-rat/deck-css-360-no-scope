##  CSS :scope pseudo-class

A scoped ```<style>``` element is used to "scope" a selector so that it only matches within a DOM subtree, creating a ```:scope``` context.

<aside class="notes">
    <ul>
        <li>:root context = html tag</li>
        <li>child elements of this subtree will be styled according to the scoping of the CSS</li>
        <li>sibling elements and their children will remain unaffected</li>
        <li>Critisms: inline styles, party like it's 1999.</li>
    </ul>
</aside>