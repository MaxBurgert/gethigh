# Ready up!
The game lobby is in its final steps as it now provides the function to start, end and open a game. When all clients in a game lobby have pressed the ready button, the game will start automatically.
We also made changes to the logout handling for the server and client side, which fixes a bug where the client closed the window but was not properly logged off. 

Thanks to easter, we will focus this week on a basic implementation of our game loop. 
In the last days, we also made progress in our game logic. The collision detection is working but far more important is the collision handling which gave us the possibility to a basic player control. 

Have a look at this preview for milestone 3:
![alt text](http://imgur.com/a/M3kH5 "Screenshot")

`Max Burgert on 11.4`

# P stands for Progress
It is Tuesday again and we had our weekly team meeting where we discussed our further approach to milestone 3, presented and merged our progress on the goals which we agreed on last week. 

After hours of trying, Tom was able to get the CI function in gitlab running on last wednesday, which should play an important factor in our quality concept measurements. Since this was also a point of critique by the tutors on milestone 2, we will investigate till next tuesday in a more concrete way of measuring and where to measure software quality aspects.

A great step towards a working game engine was made by implementing fundamentals of our game logic by adding datatructures for the map, blocks, inventory and the player objects. 

The server is now able to manage multiple game lobbies and functions with which clients can create, join, leave and list game lobbies. Those informations are now displayed on the right hand side in the lobby window. Only members of the same game lobby will receive chat messages send from other clients who are part of the game lobby. If a client is not part of any game lobby, only clients who did not join a game lobby can read those chat messages. 

Broadcasting to all clients works along with storing a highscore list.

`Max Burgert on 4.4`

# Private love messages
Today we finished and implemented the whisper function in our lobby. It is now possible to send non-public messages to a specific client. These messages therefore will only be shown to the receiving and also to the sending client.

`Tim Königl on 29.03`

# Let's have a meeting
Today we agreed on a weekly two hour meeting on tuesdays, where we want to discuss our weekly goals and agreed on deadlines for certain tasks. We also want to review our code and keep it up with the software quality concept.

Till next Tuesday our aim is to implement the management of multiple gamelobbies on the server side and the manipulation (creation, joining, leaving) of a gamelobby on the client side. Further, first drafts of our gamelogic (datastructures) on which the basic game will be based on are due to the 4th of April. 

`Max Burgert on 28.03`

# No ping, no game
Yesterday we reworked our network protocol which is now based on enums instead of Strings. We implemented chat commands through which is now possible to change ones nickname. When closing the application, the client gets now properly logged off from the server and all client side background threads are closed. With ping/pong the server now checks if the client sends signs of a working connection, if he doesn't, the server will disconnect the client after three seconds from the server. In sight of milestone 2 we reviewed our code and documented as much as we could. Today, we want to descide on our code quality concept and document our protocol in a seperate file.

`Max Burgert on 24.03`

# Chatter like a magpie
A small step for mankind, a giant leap towards milestone 2! We now got a working chat between several clients with UI implementation. Earlier this week we fixed a problem where displaying the chat in the JavaFX textarea threw a NullPointerException. Besides that, we found out that a client who is still in the login window gets an error when other clients have already begun with chatting. This NullPointer was also fixed by initializing the listening from a client to the chatroom after he leaves the login window.

`by Max Burgert on 21.03`

# Protocol and LobbyUI touches 
We created a first draft of our network protocol and worked on the Login/Lobby UI which lets us test the server/client interaction in the upcoming days. Tom and Paul also worked on a basic server/client setup based on learned topics in the lecture. Basic communication between  server and at least two clients was tested.

`by Max Burgert on 16.03`

# Restructure & CI
After we tried to add Gradle to our project lot of errors appeard, we decided to create a new clean project in Intellij with Gradle support from the very beginning.
Now we can also add Continuous Integration to our repo.

`by Tom Cinbis on 15.03`

# First Steps
We discussed properties of our networkprotocol and outlined some commands that we definitely want to implement. In addition to that, we also started to create a first draft of our Login/Lobby GUI. This should be a fun week!

`by Max Burgert on 14.03`

# Finished presentation for milestone 1
Finished presentation for milestone 1 and pushed it.

`by Tom Cinbis on 01.03`

# Added all Members to repo
Now everybody joined our repo and we can start now.

`by Tom Cinbis on 01.03`

# Hello World
In future, you can read in this blog about our game. This is an example Blog entry and will be used similar in upcoming blog entries.

`by Max Burgert on 25.02`
