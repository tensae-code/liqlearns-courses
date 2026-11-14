# Collecting Data — Sensors, Crawlers and Surveys

## Do it first

A weather station on the school roof knows the temperature every minute without anyone climbing up. A researcher knows the price of the same phone in fifty online shops without visiting one. A teacher knows what two hundred parents think without two hundred conversations. Three different kinds of knowing — three different ways of collecting. This lesson separates them.

## Sub lesson 1 — Collecting from the world — sensors and records

Some data is collected by **sensors**: devices that measure a physical quantity — temperature, light, motion, water level — and record it as data, automatically, as often as needed, in places people cannot stay. A weather station, a step counter and a river gauge all work this way: measure, convert to data (digitisation at work), store, repeat. Other data already exists in **records** — registers, receipts, past results — and collection there means gathering and copying what organisations already hold. The shared rule: decide from the question what to collect, how often, and in what units, *before* collecting — data gathered without a plan usually misses the one column the analysis later needs.

[Picture — the school roof weather station with a dotted line of readings flowing down into a growing table on a notebook below]

## Sub lesson 2 — Collecting online — web crawlers and questionnaires

Data that lives on web pages can be collected by a **web crawler**: a program that requests a page, reads its structure, extracts the items that match (with a library such as Python's **BeautifulSoup**, which parses the page's HTML into findable parts), stores them, and moves to the next page — doing in an hour what a person with a clipboard could not do in a month, provided the collection respects the site's rules and the data's owners. Data that lives in people's heads needs the third route: **questionnaires and online surveys** — carefully worded questions, sent to the right people, whose answers return already digital. A good survey question can be answered in one tap and means the same thing to everyone who reads it; a bad one collects noise that no later cleaning can remove.

[Picture — a small spider-shaped program walking a web of pages, dropping each price tag it finds into a basket that becomes a neat table]

## Say it to your companion

Tell your companion, in your own words: sensors collect from the world automatically, records are gathered from what organisations hold, a crawler with a tool like BeautifulSoup extracts data from web pages, and surveys collect from people — and the question being answered decides which route, how often, and in what units. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: name the collection routes: sensors, existing records, web crawlers, questionnaires/surveys — and say what each is for. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: describe what a web crawler does, step by step, and what BeautifulSoup does inside it. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: say what makes a survey question good, and why a bad one cannot be repaired later. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: choose a collection route for a given question and defend the choice. Do this with a real example of your own and write or say how you know it is right.
