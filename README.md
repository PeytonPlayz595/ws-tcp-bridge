TCP to WebSocket proxy
=============

A TCP to Websocket proxy made using nodejs

WIP - the actual code is extremely simple, it has been tested and seems pretty stable, feel free to help.

*NOTE* - Only supports binary WebSocket frames.

# INSTALL

**nodejs must be installed first before using this server.**

Download this GitHub repository and extract the zip file, you can download from the main page or use `git clone https://github.com/PeytonPlayz595/ws-tcp-bridge`

# How to use

Once you've downloaded and extracted the GitHub repo you need to cd into the folder and run the proxy using node

example:    
```$ node ws-tcp-bridge --websocket 8080 --minecraft localhost:25565```

proxy mode ws -> tcp    
forwarding port 8080 to localhost:25567

You need to replace "8080" with the port you want your websocket server to be hosted on and replace "localhost:25565" with the IP address of the Minecraft server you want to proxy over to WebSockets.
