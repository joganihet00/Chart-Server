# Chart-Server

LiveChatServer is a Live CHATROOM which allows multiple users (Clients) to chat with each other.


Features
Multiuser Live Chat
Awesome GUI + Console mode option
Password Encryption
Error Tracking by writing them into a log file
Usage
First run the Server Program by providing the four parameters - Port No, Datbase host, Database username, Database password

java -jar server.jar port_no datbase_host your_database_username your_database_password
Run the Client program by providing the server host and port no

java -jar client.jar server_host server_port_no
The above command opens the GUI mode. If you want to open the standard console mode then specify extra --console option while running the client program

java -jar client.jar server_host server_port_no --console
Console Commands or hidden commands ( can be typed as a message )
For Sending personal message in live chat group

@username **message**
( this will show up as a PM on that particular user's screen )

For Exiting from Live Chat Group

sv_exit
For logout

sv_logout
For getting the list of online users in room

sv_showusers
It's not a BUG. It's a feature!
Create a SECRET ROOM!!
i) First create a new chat room by leaving the name of the chatroom empty or by providing spaces.
ii) Now you can join the above created room by specifying empty name or the spaces you provided while creating the room in join room option.
iii) This room won't be visible / displayed in the view rooms list!
Collaborate with us!
Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

Fork the repo
Create a new branch (git checkout -b improve-feature)
Make the appropriate changes in the files
Add changes to reflect the changes made
Commit your changes (git commit -am 'Improve feature')
Push to the branch (git push origin improve-feature)
Create a Pull Request
Bug / Feature Request
If you find a bug (the application couldn't handle the query and / or gave undesired results), kindly open an issue here.

If you'd like to request a new function, feel free to do so by opening an issue here.

Screenshots
Sign In Activity


Main Menu Activity


View Rooms Activty


Chat Activity


License
See LICENSE
