# Original arras.io Source Code
https://github.com/nepphhh/arrasio

# arrasio-chat-system
Chat system for arras.io (diep2). Press 'H' key to show chat textbox and players list dropdown list.

# Changes required
- Find "Chat System" for the changes required in app.js, canvas.js, globals.js, server.js, etc.

# Features
- Basic authentication
    - Type '/pwd PassWord' in chat to authenticate
    - Default passwords are 'owner' for 'Owner' role, 'admin' for 'Admin' role, 'moderator' for 'Moderator' role, etc.
- Chat colors
    - Chat messages have different colors depending on player role. Default color is 'white'.
- Chat commands
    - PM (private message) a player (select a player from '- All -' dropdown list and type your message)
    - Mute for 5 minutes (select a player from '- All -' dropdown list and type /mute)
    - Unmute (select a player from '- All -' dropdown list and type /unmute)
    - Kill your own tank (type '/km')
    - Count all players (type '/countall')
    - Count dead players (type '/countdead')
    - Turn on/off chat (type '/chaton' or '/chatoff')
    - Turn on/off PM (type '/pmon' or '/pmoff')
    - Turn on/off swear filter (type '/sfon' or '/sfoff')
    - List all players with their id (type '/list').    
- Swear filter (RegEx)
    - A few entries are included to filter words such as 'sh*t'.

# Tools used to build and run the game:
- gulp
- npm
- Node.js

# Demo Server 1
Initial loading time may take a while.
http://arras.cc

# Demo Server 2
Initial loading time may take a while.
http://arras.pro

# Demo Server 3
Initial loading time may take a while.
http://arras.fun

# Screenshots
Here are some screenshots of the game with chat system in action.

[Start page]
https://imgur.com/1wbe7Ij

[Chat message to all]
https://imgur.com/cCQeX02

[Typing a private message]
https://imgur.com/39irZso

[A player receives a PM in yellow color]
https://imgur.com/Hxx95fy

[Chat command - authentication]
https://imgur.com/SMgZxwQ

[Colored chats]
https://imgur.com/fDUKJHk

    
