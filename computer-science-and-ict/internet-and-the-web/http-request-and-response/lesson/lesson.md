# HTTP — how a web page is requested and delivered

## Do it first

You click a link. A moment later, a page stands on your screen. Four things just happened, in order, too fast to see. Work out your best guess of the four — who asked, who answered, and what travelled each way — then read the real order.

## Sub lesson 1 — The round trip — request, connection, data, response

**HTTP** — **Hypertext Transfer Protocol** — is used to **access data on the World Wide Web**. It is a **request–response protocol** between a **client** (the browser user) and a **server** (the web host). The round trip, in order: **(1)** the client sends a **request**; **(2)** HTTP has the **connection made through TCP**; **(3)** the request reaches the server, which **picks the requested data from its database**; **(4)** HTTP sends the **response back to the client**. HTTP also **formats and transfers web page data** — text, images and video. Watch the GIF and follow the dot: request out, page back.

[IMAGE 11724 — the HTTP round trip in four steps]

## Sub lesson 1 — The round trip, shown moving

Follow one request all the way round once more in the GIF — out as a question, back as a page.

[GIF 11725 — a request out and the page back]

## Sub lesson 2 — HTTP beside SMTP — and two more protocols named

HTTP is **likened to SMTP** because client–server data in both looks like SMTP messages — but they differ in **how messages are sent**: **HTTP messages are not read by humans and are delivered immediately**, while **SMTP messages are stored and forwarded**. Two more protocols are named alongside: **IMAP** and **NTP**.

## Say it to your companion

Tell your companion the four steps of the round trip in order, who the client is, who the server is, and one way HTTP differs from SMTP.

## Do It Yourself

1. Draw the round trip: browser, server, and the two journeys between them, numbered 1 to 4.
2. Write who the client is and who the server is, from memory.
3. Complete the contrast: HTTP messages are delivered ______; SMTP messages are ______ and ______.
