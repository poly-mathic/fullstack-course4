# COMBINING SELECTORS
## apply styling to specific elements 
## Element with Class Selector
```css
p.big { font-size: 20px;}
<p class="big">...</p>
```
> every p that has class "big" will be 20px
---
## Child Selector 
```css
article > p {color: blue;}
<article>...<p>
```
> evrey p that is a DIRECT child of an article
---
## Descendant Selector
```css
article p {color: blue;}
<article>...<div>...<p>
```
> every p inside article at any level of article
---
## Not limited to element selectors
```css
.colored p {color: blue;}
``` 
> every p that is inside an element with class="colored" (at any level)
```css
article > .colored {color:blue;}
```
> every elmt, with class=colored & direct child of article element
---
## NOT COVERED
* Adjacent Sibling Selector (selector + selector)
* General Sibling Selector (selector ~ selector)
