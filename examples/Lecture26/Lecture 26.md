# BOOTSTRAP GRID SYSTEM
Basics
```html
<div class="container">
    <div class="row">
        <div class="col-md-4">Col 1</div>
    </div>
</div>
```
Bootstrap grid must always bin in a container wrapper. or container-fluid. 
container-fluid stretches layout to full browser width and provides consistent padding around grid and content
Container has fixed width that is still responsive basedd on browser width break points  
Row creates horizontal groups of columns which collapse and interact with eachother as a group, but independently from columns  in another row. creates a negative margin to counteract the padding that the container class sets up  
<img src="no negative margins.png">
<img src="neg marg.png">
 ## Column Class
 col-SIZE-SPAN
 *SIZE = screen width range identifier.
    * MD, LG, etc.
    * identifies at which breakpoint column
 * Colums will collapse (and stack) below that width size defined. Unless another rule specified
 * SPAN = how many colums elms should span (1 to 12)
 * 

