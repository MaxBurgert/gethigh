# Let's have a meeting
Today we agreed on a weekly two hour meeting on tuesdays, where we wnat to discuss our weekly goals and agreed on deadlines for certain tasks. We also want to review our code and keep it up with the software quality concept.

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
