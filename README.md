# Talkito
Chat Application for personal & group chat.


## Tech Stack to be used: 
- Use Web Socket Programming
- Java Spring Boot for Backend
- Angular.Js for frontend


## Features
- Built with Spring Boot
- User login
- Chat message broadcasting and private messages (filtering profanities)
- Presence tracking sending notifications when users join / leave
- Broadcast notifications when users are typing
- WebSockets stats exposed at /stats
- WebSocket security with Spring Security
- Spring Session integration


## Setting up development environment
Clone project repository

    $ git clone https://github.com/C0deAttackC0mmunity/Talkito.git

Change working directory to project folder

    $ cd Talkito

Run the app

    $ mvn spring-boot:run
  The server will start on port 8080.

Visit [127.0.0.1:8000](127.0.0.1:8000) on your browser to chat.
