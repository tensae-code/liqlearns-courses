# SQL injection

## Do it first

A website's login box expects a name and a password. What if someone types not a password, but a piece of database code — and the website obeys it as an instruction? That smuggled instruction is this lesson's attack.

## Code through the front door

An SQL injection happens when an attacker injects unauthorised input into an SQL statement. SQL is the language websites use to talk to their databases — so the attacker is not guessing at the door; they are slipping instructions through it, written in the database's own language.

[Picture 20912 — SQL injection — code slipped in behind a password]

## Where it can happen

It is possible only on websites where the hacker can reach the database using a user's ID and password — the login route is the route in. That is why this small lesson sits among the eight: the same box that welcomes a user can be used to smuggle a command.

## Say it to your companion

Tell your companion, in your own words: in an SQL injection, an attacker slips unauthorised input into an SQL statement through a website that lets a user reach its database. Then name the key words of this lesson — SQL injection, SQL, injection, where it works — and say what each one means.

## Do It Yourself

1. Explain 'injection' with the login-box drawing.
2. Say how SQL injection differs from a password attack.
3. Write why the login route matters to this attack.
