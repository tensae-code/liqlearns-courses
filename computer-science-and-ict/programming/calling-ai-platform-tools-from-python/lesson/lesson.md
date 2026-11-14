# Calling AI Platform Tools from Python

## Do it first

You could never write a program that understands spoken Chinese from nothing — that takes years and mountains of data. But a platform has already built that ability and left a door in it: your small program knocks with a request, the giant tool answers. In this lesson your program learns to knock — and builds a chatbot that really talks.

## Sub lesson 1 — AI platform tools and how a program calls them

An **AI platform** is a service that gathers trained AI abilities — speech recognition, language understanding, image recognition, question answering — and offers each as a **tool** other programs can use. The program does not contain the AI; it **calls** it through the tool's interface: it packages a **request** (the text to understand, the sound to recognise, plus the key that identifies the caller), sends it to the platform, and receives a **response** carrying the tool's result, which the program then uses like any other value. The pattern is the client's pattern from the email and chat lessons, one level up: your program is the client; the platform's tool is the server; the intelligence lives on the far side of the call.

[Picture — a small student program at a counter, handing a sealed request envelope across to a vast machine room labelled AI PLATFORM, and receiving a small answer card back]

## Sub lesson 2 — Building a WeChat chatbot

The book's practical joins the calls into a working thing: a **chatbot** on WeChat, the messaging app. A Python library for WeChat (the book uses **itchat**) lets the program log in to an account, notice each arriving message, and send replies. The program's loop is small: receive a friend's message → call the platform's intelligent tool with the message text → take the tool's answer → reply with it. To the friend, the account now converses; in truth a few lines of Python are carrying messages back and forth between the friend and the platform's AI. The lesson the practical teaches is the volume's deepest: a programmer's power is not only writing intelligence, but **composing** — joining ready tools with a little code of your own into something new.

[Picture — a phone chat: a friend types a question, the message hops to a small Python program, across to a glowing platform, and back as an answer appearing in the chat]

## Say it to your companion

Tell your companion, in your own words: AI platforms offer trained tools through interfaces; your program sends a request and uses the response, the way a client uses a server; and with a WeChat library like itchat carrying messages, a few lines of Python plus a platform tool make a working chatbot. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what an AI platform tool is, and what a request and a response carry. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: explain the pattern: your program is the client, the platform's tool is the server, the intelligence lives across the call. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: describe the chatbot loop: receive, call the tool, take the answer, reply. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: say what 'composing' means here, and why it multiplies a programmer's power. Do this with a real example of your own and write or say how you know it is right.
