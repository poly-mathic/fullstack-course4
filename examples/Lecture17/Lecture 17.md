# Conflict Resolution
Cascading is a fundamental feature of CSS, algorithm that defines how to combine properties originating from diff sources.  

Cascade Alg combines importance, origin, specificity and source order of applicable style declerations to determine what decleration to apply to what element AND how to resolve conflicts/which css rule wins  
CONFLICT = when two declerations specify the same property for the same target
## Some Concepts
* Origin Precedence (when in conflict)
  * kicks in when properties in conflict 
  * RULE = Last decleration wins, precedence
  * External CSS is declared at the spot it is linked to, usually the head
* Merge
  * when NOT in conflict (css dec target same element but different properties) RULE = MERGE
    * ex. font size and color in two place will be merged
* Inheritance
  * DOM Tree (Doc Object Model). Specifiy some css property on element, all the children will inherit property
* Specificity
  * RULE = Most specific selector combo wins
  * Specificity scoring (high to low) asign a one to each cat per appearence then count
    * !important
    * style=".."
    * ID
    * class, psuedo class, attribute
    * "#" of elements used 