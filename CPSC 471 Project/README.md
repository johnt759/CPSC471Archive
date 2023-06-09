
Group Project

Group Members: Vincent DeAugustine, DIeter Sparks, Jaemin Jin, John Tu, John Gomez

TCP server and client applications 

How to execute:

Run server application:

	Go to the directory called OurTCPServer in terminal
	
	In the terminal enter:
	
		python3 serverApp.py <port number>
		
		(<port number> is any port number you want to choose)


Run client application:
	
	Go to the directory called OURTCPClient in terminal
	
	In the terminal enter:
		
		python3 clientApp.py <server address> <port number>
		
		(we recommend you use 'localhost' as the server address, that is the 				address we used for testing)	


You will be prompted with 'ftp>'

Enter the commands 'ls', 'put', 'get', or 'quit'

Note: due to some unforseen circumstances, we were unable to complete the get and put commands. The 'ls' command is completed and should be functioning properly. The applications are able to connect to each other through a TCP socket and send information to and from one another. 