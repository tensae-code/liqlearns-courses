# Event Viewer — reading the error log

## Do it first

A program crashed yesterday at break time, and nobody saw why. Windows, however, wrote it down. Write where you would look for that written record. Then follow the book's three steps to open it.

## Sub lesson 1 — Opening Event Viewer

When system or application errors occur, **Windows records them in Event Viewer**. Open it the book's way, in three steps:

1. Click the **Windows search box**.
2. Type **Event Viewer**.
3. **Open Event Viewer** from the results.

[Picture 17706 — the Event Viewer window with its three Windows logs labelled and one error opened in detail]

## Sub lesson 2 — The Windows Logs and what an event records

Events sit in **categories**. Most troubleshooting uses the **Windows Logs**, three of which the book names:

- **Application** — events from **system components such as drivers** (as the book assigns them).
- **System** — events from **installed programs** (as the book assigns them).
- **Security** — **logon attempts and resource access**, recorded when security logging is on.

Every recorded event carries the same facts: **what problem occurred, its date and time, its severity, its source, its event ID number, and which user was logged in**.

## Sub lesson 3 — Reading one event in full

**Double-click an entry** and its full detail opens. Read the facts in order — what, when, how severe, from where, which ID, which user.

If the detail still does not hand you the fix, the book's standing move applies: **searching the internet may still be needed** to find it — the event ID and source are the words to search.

> **Teacher evidence:** Event Viewer is opened on a real machine in the class demonstration, to show logged hardware errors where they actually live (teacher guide, printed p. 91).

## Say it to your companion

Walk your companion through opening Event Viewer in three steps, name the three Windows Logs and what each holds, and list the six facts every event records.

## Do It Yourself

1. Write the three steps to open Event Viewer, in order, from memory.
2. An error happened at 10:15 while a pupil was logged in. Write the six facts the event will show about it.
3. You double-click an event and still cannot see the fix. Write your next move, in the book's words.
