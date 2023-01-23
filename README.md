# UOCIS322 - Project 1 #

## Auther: Daniel Willard 
## Contact: dwillar4@uoregon.edu

## Description:

This project we biuld a basic web server. 
We modify the pageserver.py file to handle requests form the the user the the response function. 
the config.py file searches the whole file structure for the creditial.ini file to set up the basicfunctions of the server.  
The server only takes the fallowing possible cases:

* 1) is is a get request if not return 401

* 2) does it have legal characters if not return 403

* 3) does the requested file exist if not return 404

* 4) if all the above are true, get the page and serve it to the client.
 

we modify the code form printing out a cat to handling requestes and allowing access to the files in the pages folder.

we then send the page to the requester.

the listen function creates a server socket to listen to.
the serve fuction resonds to connection
the trasmit function sends the message out
the get-options function gives you options form the configuration file or the command line.



