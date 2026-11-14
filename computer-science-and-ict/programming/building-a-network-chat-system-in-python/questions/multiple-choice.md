# Building a Network Chat System in Python — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) In a chat system, a message from one client travels —**
a) directly to every other client  b) to the server, which broadcasts it to the other clients  c) only to the nearest client  d) through the email servers
**Answer: b) to the server, which broadcasts it to the other clients** — The server is the meeting room; everything passes through the middle.

**2. (Sub lesson 1) Broadcasting means the server —**
a) saves the message for a week  b) passes the message on to all the other connected clients  c) translates the message  d) deletes the message
**Answer: b) passes the message on to all the other connected clients** — One message in, a copy out to everyone else.

**3. (Sub lesson 2) WebSocket is used for chat because it —**
a) compresses messages  b) keeps a connection open so both sides can send at any moment  c) works without a server  d) sends messages by post
**Answer: b) keeps a connection open so both sides can send at any moment** — One-shot requests are too slow a rhythm for live chat.

**4. (Sub lesson 2) The client program's two jobs are —**
a) sending and deleting  b) listening for arriving messages, and sending typed lines  c) connecting and charging  d) storing and printing
**Answer: b) listening for arriving messages, and sending typed lines** — It must do both at once.

**5. (Sub lesson 2) If the server program stops, the chat —**
a) continues without it  b) keeps working client to client  c) stops — clients have no middle to pass messages  d) sends by email instead
**Answer: c) stops — clients have no middle to pass messages** — Every message's path runs through the server.
