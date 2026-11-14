# Building a Simple Email Client — short answer

Answer each question in a few sentences.

**1. (Sub lesson 1) Explain why email needs servers at all — why not send straight to your friend's computer?**
**Answer:** Because the friend's computer may be off or unreachable when you send. Servers are always on: the sending server takes your message at any time, and the receiving server holds it in the mailbox until the friend's client comes to collect it.

**2. (Sub lesson 2) Your sending program connects and logs in, but the message never arrives. Name two things to check before rewriting the code.**
**Answer:** The server address and port (they must be the SMTP ones for that mail service), and the receiver's address as composed in the message — a single wrong character sends the mail nowhere; also check whether the server rejected the message and printed an error the program ignored.
