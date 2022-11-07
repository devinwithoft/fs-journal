# JavaScript

load javascript with
<script src="app.js" tag>

basics
console.log()


// primitive 
let string = "hello"
let number = 5
let number2 = 5.67323
// let bool = true or false
let dontknow = undefined //unknown nothing
let nothing = null //know nothing

//reference
//arrray store info by index/position/order
let arr = []
let strArr = ['1', '2', '3']
let numArr = [ 100, 300, 400]
let mixArr = ['5', 10 ['sup']] // try to avoid

//open array by
strARr[0]

//store as Key Value pair
let obj = {
    key: 'value',
    name: 'devin',
    costume: 'cheese'
}
mixing string number okay

pull by
obj.name
obj[name]
order not good...

reference points update

cares about reference not value when comparing arrays
==

function dosomething(){
    console.log('swag')
}

let funky = function(){
    console.log('funnky')
}

let funcArr = [funky]
funcArr[0]
function returnSomething(){
    return 'hello'
}

returns to whatever called it
like 
console.log(returnsomething())

event handlers add events to handles

onlick = "returnsomething()"
onblur
onfocus
ondrag
ondragStart

x += add and then changes x
cant subtract / multiple / divide strigns

= is assignment 

write line always console.log it 

window.alert('string')

function drawCode(
    let codeElm = getdocument.getElementById('your-code')
    console.log(code.Elm);
    codeElm.innerText = yourCode
)

but id = ""in HTML where you want it show up

debugger


DAY TWO

define objects then put in ray

xArr [object1,2,3]

or 

xArr[
    {
        key:value
    }
    {
        key:value
    }
    {
        key:value
    }
]

pulling specific object

xArr[x].key

deeper 

Can insert objects into any array
xArr[x].key[1] pulls up "k"

for (let index = 0; index <= 11, index++){
    console.log("looped")
}

1st initlizer, 2nd comparison,  4th afterthought{
    3rd 
}

index <= catArr.length -1;
or
index < catArr.length

const element = array[index];
const NAME = array[index]; // an alias 
element same as entry in array 

loop array start at zero

const = cant be changed for object reference 
let x = can be changed.

catArr.forEach(() => console.log("for each"))
same as for loop^
catArr.forEach ((alias-belement, alias-index) => console.log (cat.name))

() => lambda
just need a function and ill run it 
anonymous function, no name.

catArr.find <- iterates through array

catArr.find(cat => cat.name == 'Fido')


//find gets reference to single element of array to operate on
let foundByName = catArr.find(cat => cat.name == 'Fido')
console.log(foundByName.name)

let foundByAge = catArr.find(cat => cat.age > 5 )
console.log('found':, foundByAge) ///finds FIRST, and single cat

// finding multiple
catArr.filter ()

.includes array method


catArr.sort((cat1, cat2) => cat1.age-cat2.age)
current element, next element

|| OR
&& AND
! NOT 

                |
single value    V
switch(Randomclue){
    case 'key'
    break
    case 'pls'
    break
}

case IF 

Math.floor(Math.random)*array.length


.join elements buts all elements into a string
.join (' and ')


? 'true' : 'false'
innerText vs innerHTML

`you can use this to include ${objects} `


% 2 == 0 even
% 2 == 1 odd

turnary %

return num % 2 == 1 ? true : false 
ternary

(return num % 2 != 0)

toString = return number to string in HTML
toFixed(2) = round number to string rounding to (2) decimal places for HTML

window.confirmn

REFER TO OTHER FUNCTIONS 

    USE LET TO PULL ITEMS OUT OF ARRAY


if (window.confirm("Are you sure")) {
    sandwiches.forEach()
}

    let LOOKINGFOR =  sandwiches.find (s => sandwiches.name)
   
    

sandwiches.fitler

let p = function (){}

let a 
a = () => {
    blah blh; 
} 


intervals


let interval = setInterval(()=> {console.log('hi'), 4000}) 4s
setTimeout(()=> clearInterval(Interval), 40000) 
clearInterval  