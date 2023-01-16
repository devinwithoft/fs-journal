# MVC

===========================Below are just notes for 12/1===========================

Steps for tomorrow

1. Someone makes respository 
set environment variables (.env) & (env.js)
in connection string after mongodb.net you can set project name

**who ever makes repository needs to slack out their settings**

.env isnt pushed in gitHub so manually have to write it



2.  on Github "collaborators and teams" add your people
people have to accept, and then clone down repository 

test pushing today

3. seperate 2 back end / 2 front end
both squads working on one laptop each


Now to the project 

from models
 
enum, for string. essentially gives you a few set options for your string that will be accepted

For middleware
.use(Auth0Provider.getAuthorizedUserInfo)

to grab token, go to network tab > preview > copy token

in postman authorization, set bearer token for whole domain

in create 
req.body.(IDNAMEHERE) = req.userInfo.idc
**note**
in schema the IDNAMEHERE has to be an type: **Schema.Types.ObjectId**

do .get(all) .get(getbyID) and .create



**FRONT END**

Start with model, using server as reference

Create somewhere to save (appstate) empty array for models

per usual => controller & service both exported, controller imported into app

Consult axiosService for name of accessing server

to troubleshoot for front end, use network tab

be sure to MAP before saving into app state. res.data.map(x => new ClassName(x))


to use SASS

**In console on project npm i bootstrap**
**then npm run sass**


fixing img sizes
class width: 100%
height: staticvh
object-fit:cover


**Back to back end**

Form data

hav to getFormData(form)

for .populate('nameofvirtual anothervirtualname', 'nameofdatayouwant nameofotherdata')


**req.userInfo.id**

all account stuff ^ 

CreepSchema.index({ creepId: 1 , birdId: 1}, {unique:true})


mongoDB compasss

my mongo DB

drop collection
cd sourc

NPM I




