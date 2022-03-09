# Chess!

I'm interested in making a chess server and client to play against the computer. Initially
I'm thinking:

- python api using the pypi `chess` package and stockfish engine
- javascript client using chessjs for legal moves and display

Helpful links:

- https://github.com/niklasf/python-chess (probably using this in the backend, to avoid reinventing the wheel...although I do love reinventing the wheel)
- https://github.com/nomemory/neat-chess (simple example UCI implementation that I might use if I hand roll something like the python-chess lib)
- https://github.com/jhlywa/chess.js (js library for validating positions and legal moves, etc)
- https://github.com/Clariity/react-chessboard (great resource for drawing boards and pieces)

Design:

- work in progress of course, but either a websocket connection from js to python, or just a simple HTTP/REST type thing, with messages being like "move here", "undo", "restart", etc
- I don't know anything about websockets (like auth, reconnecting, timeout...etc) so it's either a great opportunity or a time sink!
