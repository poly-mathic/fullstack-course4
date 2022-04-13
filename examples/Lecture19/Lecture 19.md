# THE BOX MODEL
every element is considered a box  
theres more to the box than just the content, theres also padding, border and margin (from inside out).  
BOX MODEL is the components that make up the box and the rules that govern how the box affects layout.  

USE THIS TO SET WIDTH OF BOX NOT JUST CONTENT
```css
* {
    box-sizing: border-box;
}
```
box sizing prop is not inherited.  
Use wildcard selector, to merge new default values accross whole doc. over riding the user-agent-stylesheet. CSS resetting

## CUMULATIVE MARGINS
two boxes next to eachother will have cumulative margins (50px + 40px = 90px)  
two boxes top to bottom will have collapsed margins, larger margin wins (50px + 40px = 50px)  

## OVERFLOW
use this property to dictate how to deal with content spilling out of constrained boxes. Too much text in a box with a fixed size.
```css
overflow: auto;
```
this will add scroll bars wherever needed. but double scroll bars suck.

