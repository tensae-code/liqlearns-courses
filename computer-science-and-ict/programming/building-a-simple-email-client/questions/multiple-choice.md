# Building a Simple Email Client — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) SMTP is the protocol used to —**
a) fetch mail from a mailbox  b) send mail to a mail server  c) compress mail  d) write mail
**Answer: b) send mail to a mail server** — SMTP pushes mail out from client to sending server.

**2. (Sub lesson 1) When the receiver's computer is switched off, a sent email —**
a) is lost  b) waits in the mailbox on the receiver's mail server  c) returns to the sender at once  d) stays on the sender's computer
**Answer: b) waits in the mailbox on the receiver's mail server** — Servers hold mail until the client collects it.

**3. (Sub lesson 1) IMAP differs from POP3 because with IMAP the messages —**
a) are never delivered  b) stay on the server while the client reads them  c) travel without a server  d) can only be sent, not read
**Answer: b) stay on the server while the client reads them** — POP3 downloads; IMAP reads in place.

**4. (Sub lesson 2) In Python, the module that speaks SMTP is —**
a) poplib  b) smtplib  c) websockets  d) email only
**Answer: b) smtplib** — smtplib connects, logs in and sends.

**5. (Sub lesson 2) The correct order for the sending program is —**
a) send, connect, log in, compose  b) connect, log in, compose, send  c) compose, send, log in, connect  d) log in, send, connect, compose
**Answer: b) connect, log in, compose, send** — First reach the server, prove who you are, build the message, send it.
