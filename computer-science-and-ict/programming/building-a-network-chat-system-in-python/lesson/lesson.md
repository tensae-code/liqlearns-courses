# Building a Network Chat System in Python

## Do it first

Email is a letter: you send it and wait. Chat is a conversation: the words appear as they are typed. The difference is the connection — chat keeps it open, talking both ways at once. In this lesson you build that: one server, several clients, messages flying between classroom computers.

## Sub lesson 1 — How network chat works — server in the middle

A chat system has the same two kinds of program as email, arranged differently. The **server** runs in one place and waits. Each user's **client** connects to it and stays connected. When one client sends a message, it goes only to the server; the server then **broadcasts** it — passes it on to every other connected client, whose screens show it at once. The server is the meeting room: nobody talks across the room directly, everything passes through the middle, which is also how the server can keep order, note who is present, and record what was said.

[Picture — five computers in a ring with one server in the centre, arrows running from each computer only to the centre and back]

## Sub lesson 2 — Building it with Python and WebSocket

Ordinary web requests are one question, one answer, then silence — too slow a rhythm for chat. **WebSocket** is a protocol that opens one connection and keeps it open, so both sides can send at any moment: that is what live chat needs. In Python, a WebSocket library gives the server its shape: accept each client's connection, keep the list of connected clients, and whenever a message arrives from one, loop through the list and send it to all the others. The client program is smaller: connect, then do two jobs at once — listen for arriving messages and show them, and take typed lines and send them. The book's practical runs server and clients on the classroom network until the room is chatting through code the students wrote.

[Picture — three chat windows on three screens: a line typed in the first window appearing a moment later in the other two]

## Say it to your companion

Tell your companion, in your own words: in a chat system every client connects to one server and stays connected; a message goes to the server, which broadcasts it to all the other clients; WebSocket keeps the connection open both ways, which is what makes chat live. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: explain the shape of a chat system: one server, many clients, all messages passing through the server. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: say what broadcasting means and why the server does it. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: say why chat needs WebSocket's always-open connection rather than one-shot requests. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: describe the server program's loop and the client program's two jobs. Do this with a real example of your own and write or say how you know it is right.
