# MVC

hardly use html anymore


pages and components

services remain the same

appstate a little different but remains the same

model is different


controllers become components


components have 3 parts
1. <template></template>
2. <script>javascript</script>
3. <style>

debug console  

@click

import {ref} from 'vue'
vuePoints: ref(0) 


in app state
vuePoints: computed(() => AppState.vuePoints) 
tempa


for anything to reach 
return appstate

dont define async inside of return.  



client => env.js
server => .env

spin both up

log in?


account error = server 



BACK END NOTES

model

export const NameSchema = new Schema({
  title: {type: String, required true},
  category: {type: String, enum: [animals, games, crocs, misc]}
})

id is Schema.Types.Object id NEEDS A REF

in controller 

export class XController extends BaseController {
  constructor(){
    super('api/albums')
    this.router
    .post('', this.create)
  }

  async create(Req, res, next)
  const album = await albumsService.create(req.body)
  return res.send(album)
}