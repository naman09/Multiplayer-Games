# Multiplayer-Games
OST Project Sem-6

# Project Overview

The aim of the project is to show working of a client server application with the help of socket programming. Best application to show this is through a massive multiplayer online game which has hundreds of clients interacting simultaneously with the server.

For this project, we have created a server which accepts up to 100 requests from clients connected in a local area network. In this way any computer which has the server- side code can act as a server by sharing it's private IP address and then every player can connect to it.

# How it works?

One computer will act as the server and run server side code which will receive necessary data (player position, etc.) from each client (players), then it will broadcast this data to all the clients(other players) and each of them will use this data to update their game state.

