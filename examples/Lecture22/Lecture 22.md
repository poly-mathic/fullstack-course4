# RELATIVE AND ABSOLUTE ELM POSITIONS
specify precise offsets to move target elements to diff part of page  

## STATIC POSITIONING
normal document flow. default setting for all elements. applying static to elm will ignore other positioning  
default for all elms except html

## RELATIVE POSITIONING
Offsets the elem relative to its normal doc flow  
element is positiond relative to its position in normal doc flow. offset from default
* top, bottom, left, and right
creating anchor for offset from edges.  
not taken out of doc flow, original spot is preserved as far as the doc knows (opposit of floating)
```css
p{
    position: relative;
    top: 50px;
    left: 50px;
}
```
will move it FROM the top 50px, and FROM left 50px. rest of doc will act as if it has not moved  
\<html> is the only element that is REL by default

## ABSOLUTE POSITIONING 
Is relative to closes ancestor with pos set to non-static
all offsets are relative to the position of the nearest ancestor with positioning other than static.  
Element taken out of doc flow, other elms will ignore it, it is only bound to its parent. if parent moves it moves.

##