# Building a Network Chat System in Python — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) A late joiner can be noted by the server because all connections pass through it.**
**Answer: True** — The server keeps the list of connected clients.

**2. (Sub lesson 2) Chat clients must take turns, one request and one answer, like letters.**
**Answer: False** — WebSocket keeps the connection open; both sides send at any moment.

**3. (Sub lesson 2) The server program keeps a list of the clients currently connected.**
**Answer: True** — It needs the list to broadcast to them.
