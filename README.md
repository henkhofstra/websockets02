# CHAT
Je kunt dit chat programma gebruiken in een klein lokaal network. Het bouwt een locale server en gebruikers die verbonden zijn met dit netwerk kunnen in een groep een prive chat beginnen. De chat heeft ook faciliteiten om mensen te verhinderen om met pings de chat binnen te komen.

# Instructions 
Clone het project
```
git clone https://github.com/henkhofstra/websockets02.git
```

### DataBase - Mongo
* Controleer of Mongodb draait !

### Server
* Node en NPM moeten op je computer geïnstalleerd zijn.
* Open een dos promt en ga naar map websockets02.
* Installeer nu de applicatie: 
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`npm install`  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`npm install -g nodemon`  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`npm start`  
Your server will be setup and ready for use.

### UI
* Go to browser and type `localhost:8080` in place of url.
* Register user by giving basic details.
* Login from the same screen.  
`Note: Handle should be unique for every user.`

# Why I started this
I had seen a lot of times during local camps that people find it difficult to interact with each other may be due to hesitation. Most of the local chats that we find will be again public and the interactions become public. So I was thinking of creating an application where people can talk in public as well as private.

# Few Screen Shots
#### Login Screen
![login screen](https://github.com/sudheeshshetty/Chat/blob/master/screenshots/login.png "Login Page")  
#### Confirming request 
![Confirming request to chat](https://github.com/sudheeshshetty/Chat/blob/master/screenshots/confirm_request.png "Confirming Request")  
#### Online users
![online users](https://github.com/sudheeshshetty/Chat/blob/master/screenshots/online_users.png "Online users")  

#### Chatting with Friend
![Chatting](https://github.com/sudheeshshetty/Chat/blob/master/screenshots/chat.png? "Chatting with Friend")

# Upcoming
I have lot of things to do. 
* Bug fixes.
* More feauters to come, like blocking a user from chatting etc.  
* Option for saving chats in case you need it. For now it doesnot store the messages.

# Suggestions
If you have any suggestions please do mail me at `sudheeshshetty@gmail.com` with subject as `chat-suggestions`

# Credits
I have used some code from AdminLTE for the chat UI. The HTML and dependent CSS.  
The private chat box has been taken from [Gurdeep Osahan](http://bootsnipp.com/Gurdeep%20Osahan).
