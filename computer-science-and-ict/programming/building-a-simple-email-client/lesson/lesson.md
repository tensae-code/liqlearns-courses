# Building a Simple Email Client

## Do it first

Every day you tap 'send' and trust the mail app. But the app is only a program doing errands: it carries your letter to a sending server, and later knocks on a receiving server to collect replies. In this lesson you build that errand-runner yourself, in Python — small, simple, and really working.

## Sub lesson 1 — How email travels — servers and protocols

Email does not fly directly from your computer to your friend's. When you send, your **client** (the program you use) hands the message to a **sending mail server** using the protocol **SMTP** (Simple Mail Transfer Protocol). That server passes it across the internet to the receiver's mail server, where it waits in the receiver's mailbox. When your friend's client collects mail, it asks that server with a receiving protocol — **POP3**, which downloads the messages, or **IMAP**, which reads them while they stay on the server. Two errands, two protocols: SMTP pushes mail out; POP3 or IMAP pulls mail in.

[Picture — a letter's journey drawn as four stops — your computer, a sending server, the receiver's server with a mailbox, your friend's computer — with the labels SMTP on the way out and POP3/IMAP on the way in]

## Sub lesson 2 — Building the client in Python

Python's standard library carries the tools. The **`smtplib`** module speaks SMTP: the program connects to the sending server, logs in with the account name and password, builds the message — sender, receiver, subject and body — as one text (the `email` module helps format it), and calls the send method. Receiving uses **`poplib`** for POP3: connect, log in, count the waiting messages, fetch one by its number, and print its text. The book's practical builds exactly this: a small client that first sends a real message, then fetches and shows a real one — the moment the program works, the protocols of the first sub lesson stop being theory.

[Picture — a short Python program running: a 'message sent' line appearing, then an inbox count, then the text of a fetched message printing]

## Say it to your companion

Tell your companion, in your own words: a client sends mail by SMTP to a sending server, the mail waits in the receiver's mailbox, and the other client fetches it with POP3 or IMAP; in Python, smtplib sends and poplib fetches. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: describe the journey of an email: client, sending server, receiver's server and mailbox, receiving client. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: say what SMTP does, and what POP3 and IMAP do, and how POP3 and IMAP differ. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: name the Python modules for sending and fetching mail, and the steps each program follows. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: build (or walk through line by line) a simple client that sends one real message and fetches one. Do this with a real example of your own and write or say how you know it is right.
