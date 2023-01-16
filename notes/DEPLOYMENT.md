



COMPILE CLIENT INTO BACK END 

1 OPEN BOTH FILES  together (NOT WORK SPACE)
MAKE SURE NODE IS 16
2 GO TO magnifying glass and look for console.log

vite.config.js from client utils 
3 change outDir: '../nameofproject/client'

4 then go into terminal cd . \project.client\
will look like ..... \project\project.client

npm i
and then npm run build

hope it works?

5 render deployement 

5a build command
 start command

package json build and start should be done via template.
(change inside render)

5b "advanced" in render change environment variables
use .env (From backend) 

auth audience
connection stream
auth domain
 CONNECTION_STRING (same casing)
 AUTH_DOMAIN
 AUTH_AUDIENCE
 AUTH_CLIENT_ID




 file pathing to images can screw up a lot of stuff("file pathing")
 spacing in image names can screw things up especially! 

 be sure to put in URLS into auth0 so it works 