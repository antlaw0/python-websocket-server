#Web Chess
This application uses a python web socket to play a game of chess. There can be multiple clients connected and each has access to the game board to move any piece. This allows for flexibility in how you play. Messages are broadcast to all clients in the chat area to the left. Clicking on a game piece will select it and using the arrow keys will move the piece. When the selected piece collides with a piece of the opposite color, that piece is removed from play 'captured'.

Notes: I am currently unable to deploy this application to heroku or Python Anywhere so it just runs locally for now.

#How to run:
In a command prompt, navigate to the folder containing server.py and run the server using 'python server.py'. A message should appear stating that the server is running. You can then open up as many client.html windows as you want. Any message or piece movement will be sent to all connected clients. To stop the server, in the command prompt, press control+c and type 'exit'.

#Known Issues
Selected piece on other clients do not capture pieces like what happens on the client that is controlling the selected piece.