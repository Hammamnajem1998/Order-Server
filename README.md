# Order-Server
the main job of Order Server (in our womework) is to resend the requests comming from Order Server to Catalog Server .However , this not logical to 
build a server just to resend requests .But, on the real big applications that have to be scalable and maintainable it's appear as a necessary 
feature on the application .

So, we make this server just to give a small exercise of how distributed systems applications realy(and simply) work and communicate . 



what you want to change ? 

there is one line to change to make the server work on your machine. 
line 25 make a connection with catalog_server to ask for buy request, change the previous catalog_server URL with 
your new catalog_server URL .
