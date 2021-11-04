# Node-Chat-App

This is a simple Chat App using NodeJs, You can see live demo here : https://geek-chat-app.herokuapp.com/

![screenshot](https://github.com/AhmedAymanBfcai/Node-Chat-App/blob/main/ChatPhoto.PNG)

The project was created using Node js with WebSockets and Socket.io library, It enables users to login to different chat rooms, 
send messages and their geographical location using google maps.

## Architecture

<p align="center">
  <img src="https://github.com/start-angular/angular2-node-socket-io-chat-app/blob/master/public/Sequence-Diagram.png" alt="Node Socket.io Chat" width="800" height="577"/>
</p>

## File Structure

Here's an overview of how the files are laid out in this project:

```
chat-app
|
├── public/                  * Where our client code is stored
│   ├── css/                  * All of our chat-css styles files are here
│   │   ├── styles.css      	        
│   │   └── styles.min.css      		  
|   |   
│   ├── imgs/                        
|   |	|
│   │   └── favicon.png 					    
|   |   
│   ├── js/                    * All of our js client code is here
│     |
│       └── chat.js 		      	      
|    
├── src/                     * Server side code (socket.io,express,node)
    ├── utils/                * utils for server side
    │   ├── messages.js     	  * to generate messages all with timestamp
    │   └── users.js      		  * Storing users data (id, username, room) and control them.
    |
    └── index.js		         * App entry point
```

The project was done as a part of "The Complete Node.js Developer Course (3rd Edition)" on Udemy.
