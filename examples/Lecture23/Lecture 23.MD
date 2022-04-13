# MEDIA QUERIES
allow the grouping of styles together to target them to devices based on some criteria  
You can target a device by width, height, orinetation etc.  
CSS is capable of rendering differently if told to do so
## Media Query Syntax
```css
@media (max-width:/min-width:/orientation:/screen/print) {
    p{
        color: blue;
    }
}
``` 
@media feature resolves to some true or false val, if case is true, style is applied.  
Media features can be combined using logial operators (and,or) 
```css
@media (min-width: 800px) and (max-width: 900px){...} 
```
this will process the style if page is within a range  
Media queries should come after base styles