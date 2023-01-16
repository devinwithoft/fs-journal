.ENV useSockets turn to trye
Services client SocketSeervice.

network tab WS web socket

server server utils socket provider
handlers

ref SOCKET.io

onMounted()=> socketService.emit('SOCKET_TEST')

emit

action = magicstring how 'wizards' client can directly contact server

cann put a listener in socket service

HANDLER IN SERVER
.on('IS_TESTED' this.whateverFunction)

whateverFunction*dOESNT NEED ASYNC FOR SOCKET*(payload){
  Pop.toast(payload)
}

to make thing load for both pages 

constructor(io, socket)
io - is everybody

this.io.emit messages all vs socket doing one

togglight(){
  lightState = !lightState
  this.io.emit('LIGHT_TOGGLED', lightState)
}

make handler on front end HANDLERS FOR SOCKETS

listener from incoming socket to appstate

socketService did another listener
.on(LIGHTOGGLED, this.function)


thisfunction(payload){
  appstate.lighton = payload
}

SOCKET SERVICE FRONT END for listeners 