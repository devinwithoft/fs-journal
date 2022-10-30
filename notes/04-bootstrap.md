# Bootstrap

Containers contain rows which contain
columns

Rows cannot contain Rows
Columns cannot contain columns
Cant put column directly into container

Columns split rows space

column sizes
col-1 to col-12 sizes
12 = total row taken up

style:debug
helps color code rows containers columns granted you add class debug to body

col4*3 shortcut to create 3 colums at size 4

justify-content-x
text-center
fw-bold

random stuff

p-2
padding 2
ps-2
padding from left 2
pe-2
padding from right 2
pt-2
padding from top
pb-2
padding from bottom
px-2
padding from sides
py-2
padding top and bottom

unsplash.com

align-items-end
align items has to go onto container to move entire row AKA whatever has flex on it


#container-fluid
takes content to edge

section.row.bg-black creates a row and adds the following variables

#img-fluid
image as big as can be but keep container

w-25 width

meet the ipsums

g-3

media rules
in-fixes

breakpoints on websit

order

<!-- GENERAL DFLEX -->

JUSTIFY-CONTENT: MAIN AXIS
ALIGN-ITEMS: OPPOSITE AXIS
align-self ^^ 

This can be confusing, but align-content determines the spacing between lines, while align-items determines how the items as a whole are aligned within the containe

<row>
<column>
<h1>

all items you want moved but in a flex container



use google inspect to help test dfles (go to cotainer w deflex)
<!-- STARTING A PAGE  -->

first start SET UP ALL SECTIONS/ROWS

ALT SHIFT DOWN COPIES BAR BELOW 



<!-- SETTING UP IMAGES -->

to center h1 vertically, need to turn column into a dflex first

try min-height instead of directly setting height

20vh?

to set up background img
{
    background-image:url(linkhere);
}

background-position for bg image 


"img-fluid" keep in container?
<!-- FLOATING BUTTONS -->
try a customclass to 
transform:translateY(-1vh)

etc


<!-- ICONS -->
link:mdi
in head


<i></i> tags normally italicize
go to material design icons

<i class mdi mdi-(name of icon)></i>

mdi counts as font for size

fs-1 largest to fs-6 smallest
**to do set up snippet for bootstrap5**


<!--general notes -->
its okay to use divs for just one thing


gap - 2 
<!-- convert to mobiles -->
change images 

display d md medium block
d-md-block

set a default 

resizing divs to mobile

*d-none* 

