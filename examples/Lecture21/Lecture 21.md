# POSITIONING ELEMTS BY FLOATING
essential skills  
felxible design that can expand and contract with the browser size 
```css
#elmID{
    float:left/right; 
}
```
floated elements ar taken out of regular doc flow and positioned at the top right or left of the containing element.  
 other elems move up to fill space, will also take them out of document height for elms like div.  
To correct the flow of a parent element use
```css
div {
    clear: left/right/both;
}
```
Floated element margins NEVER collapse when touching other elemnts