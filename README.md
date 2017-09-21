# CHAT
Je kunt dit chat programma gebruiken in een klein lokaal network. Het bouwt een locale server en gebruikers die verbonden zijn met dit netwerk kunnen in een groep een prive chat beginnen. De chat heeft ook faciliteiten om mensen te verhinderen om met pings de chat binnen te komen.

# Instructies
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
Hopelijk draait je Chat server nu.

### UI
* Start je browswer en type `localhost:8080` 
* Registreer de gebruiker.
* Login vanaf hetzelfde scherm.  
`Opgelet ! Elke gebruiker moet een unieke 'handle' gebruiken.`

# Waarom doen we dit ?
We moeten nog wat oefenen en ideeën opdoen om de realtime website voor on ballon project inelkaar te kunnen draaien.

# Scherm voorbeelden:
#### Login Scherm
![login screen](https://github.com/sudheeshshetty/Chat/blob/master/screenshots/login.png "Login Page")  
#### Een request bevestigen
![Confirming request to chat](https://github.com/sudheeshshetty/Chat/blob/master/screenshots/confirm_request.png "Confirming Request")  
#### Online gebruikers
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
