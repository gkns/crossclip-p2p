# crossclip-p2p
Clipboard sync on LAN/Internet using websockets.

This is a WIP. 

Forked from : [crossclip](https://github.com/yue/crossclip)  
The change in this implementation is:  

1. Remove UDP broadcast and use web-sockets instead.
2. Add a websocket server.
3. Sync clipboard across all connected clients.
