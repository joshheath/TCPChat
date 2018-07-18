# TCPChat

A side project built during week 3 at Makers, using Ruby. 

The app works from the terminal and acts as a chatroom, allowing users to enter a username and then communicate with each other via a server. Eaxh user can send and receive messages with all other users in the chatroom. 

The server receives connections from the client(s) and saves them in data dictonaries. These keep track of which chatroom each client is in. 

## How to access the chatroom

`git clone https://github.com/joshheath/TCPChat.git`
`bundle install`
- In `server.rb` change 'localhost' on line 44 to the IP address of the server host.

## Required files for use

`server.rb`
`client.rb`
