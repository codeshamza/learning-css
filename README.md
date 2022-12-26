# learning-css 
(Bit messy because i was very begginer at that time and didn't thought that one day i will push this to github)



USE STYLE CONTAINER...style+make another file named style.css(add link.css to current also)
USE BODY CONTAINER....body{ }
FOR change background.....backgroung colour
for defining class... use dot (.)
for defining id....  use #
use * to identify elements -
for fit image in bg without fucking aspect ratio....cover in bg size
for fit image in bg completely....contain in bg size
viewport height: device height
viewport width: device width

ORDER:

bg : colour,url(image name).repeat.attachment.positio
margin+padding(4 values)...top right bottom left
margin+padding(2 values)...top bottom left right 
for setting border.....width+style+colour+border radius


FLEXBOX:(on parent element)

FOR assigining container a flex......display.flex
for changing order of items.....flex-direction
for wrapping items(responiveness).....flex-wrap
for changing position of items(horizontaly)...justify-content...
for changing position of iems(vertically)...align-items...(for removing spaces between items...align-content..)


FLEXBOX:(on children element)
for changiing order..order..
for changing position....align-self...
for growing or shrinkng item....flex-grow...flex-shrink....

CSS GRID(On parent container)
FOR assigining container a grid......display.grid
for adjusting spaces b/w grid items....grid-row-gap,grid-column-gap
for specifying widths of items.....grid-template-columns.....u can use auto and numbers depends on how many values you will enter 
for specifying height of items.....grid-template-rows.....u can use auto and numbers depends on how many values you will enter
for adjusting spaces b/w rows & columns......grid-gap rv cv;
for justifiying your content(horizontally)....justify-content center top etc
for justifying your content(vertically)....align content center top etc


CSS GRID(on child container)
for specifying span of  colmns....grid-column: 1/5 ;  (column 1 will extend to 5)
for specifying span of  rows....grid-row: 1/5 ;  (row 1 will extend to 5)
for giving item an inline behaviour....inline-grid


MediaQueries :
for changing css and for responsiveness.....@media screen and (max-width: i.e800px)  {  css   }


Transformations:
2D method...use transfom: translate( x,y )etc.
for telling from where to tranform...use transform origin: 0,centre etc

3D method...use transform:

CSS TRANSITIONS:
Transition property: to add property for transition
Transition Duration: to set the time of Transition
Transition-Timing-Function: use to set how your want the property to transform/set type in which property transform  i.e ease in,ease out
Transition-Delay: for specifying the delay for Transition
Syntax:

Transition: Transition Property Transition Duration Transition-Timing-Function Transition-Delay;


CSS ANIMATIONS:
@keyframe i.e box1{ from{ code } to { code} }
@keyframe i.e hamza{ 0%{ code } 50% { code} 100{css code} }

Properties:
Animation Name...name of Animation
Animation-Duration...how long it display
Animation-Timing-Function...use to control the time-curve  
Animation-Delay....delay from stsrt of animation
Animation-Iteration-count...Number of time Animation run
Animation Direction...Specifying direction of anime
Syntax:Animation Name Animation-Duration Animation-Timing-Function Animation-Delay Animation-Iteration-count Animation Direction;
