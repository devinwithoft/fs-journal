# MVC

view = html with button in it
controller = say somethings been clicked
service = changes the data has a result of being clicked

1/2

appstate/"store" =  single source of truth or where all apps data stored Aka where cookies are stored
model = blueprint  of what the data inside appstate wil llook like


"bcw create" 


export class Character {
    constructor(name, race, health){
        this.name = name
        this.type = type
        this.health = health
    }
}

class CharactersService
new = new classes


methods = things inside classes

in app state
characters = [
    new Character(enter data here)

]

classes have upper case to signify its a blue print
lowercase is the one that exists


models page

can

get is property of class, calculated when accesseds
get Template(){
always has to return


model can contain something that will be calculated on grab
created property that calculates itself

}

capital letter = computed property on object

on writer use getElem 

observer listener

listener

appState.on(what youre listening for, what you want to run when changed )

need = AKA set for listener

let array  = [1,2,3]
let array = [arr,4] *adds array within array

... *spread operator takes items out of array*

...arr,4
gives 1 , 2 , 3 , 4 empty space
console.log([...arr],4)
fixes it

splice

let arr[1,2,3]
arr.splice(where to start,how many items to get rid of)
splice returns the thing it took out!!

emit is basically emit 

loadstate



1 Start by building models under constructor. Export 

2 Connect to appstore after

< 2.5 @type import in appstate gives intellisense. > under that write car info. 

??

??

5 create/export controller w console log

6 tag controller to app

appState.On goes into controller constructor 

----------------------------------------------
pop

sweet alerts

async/await 

way to erase item with arrays
filterdarry = filter(c=> c.data != paramter)  <- this removes the car with paramater
[old aray address] = filteredarray

form{
window.event.preventDefault() stop btn from reset page
let form = window.event.target

getFormData <- utility class *alias out*

form has to have NAME = modal part of form
}

type = "submit"
vs 
type = "button
or reset

input required.
min length = "3"

[...] spred DUMPS array

modal lil window




save one thing in app state
.Car|Null
@type if its a single car

 

 saveState('key', value )

 static has to be uninstantiuated