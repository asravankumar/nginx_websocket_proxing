nginx_websocket_proxing
=======================

trying new nginx websockets proxy feature

References : 
- http://nginx.org/en/docs/http/websocket.html
- http://psitsmike.com/2011/09/node-js-and-socket-io-chat-tutorial/          

Instructions:
- Install node
- cd ~
- git clone https://github.com/vireshas/nginx_websocket_proxing.git
- install nginx : http://nginx.org/download/nginx-1.3.14.tar.gz
- cd ~/nginx_websocket_proxing
- change the root in nginx.conf to match the path in your system
- **start nginx**   : sudo nginx -c ~/nginx_websocket_proxin/nginx.conf -p .
- npm install -d
- node app.js

goto localhost:8081



