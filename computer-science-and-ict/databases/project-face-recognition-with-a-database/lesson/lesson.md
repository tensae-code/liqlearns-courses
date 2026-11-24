# Project — Face Recognition with a Database

## Do it first

Two of Kuwait's courses meet in one project: the AI that sees faces, and the database that remembers them. Grade 11 builds it in Term 1 as an attendance logger and grows it in Term 2 into an employee face-log system with reports. This lesson is that integration, in both its forms.

## Sub lesson 1 — Detection, recognition, and the log — the Term 1 build

The project separates two acts pupils confuse: **detection** — finding that a face is in the picture, and where — and **recognition** — saying whose it is. Detection is done with OpenCV's **Haar cascade**, a trained detector that scans the image for face patterns. What the camera sees is then **logged in an SQLite database** — a face_logs / attendance table of who was seen and when — because, as the book insists, **a database beats a text file**: the log can be queried, counted and kept honestly, not merely appended and forgotten.

In your mind's eye: detection, recognition, and the log — the Term 1 build.

## Sub lesson 2 — The Term 2 growth — employees, queries and reports that decide

Term 2 grows the logger into a system: an **employees table linked to a face_log table** (the relational year's parent and child), Haar detection feeding the log, and **queries and reports that support decisions** — who was late how often, which door saw whom — finished as **PDF reports built with ReportLab**, the program itself printing its findings. The project's lesson is the integration: neither the AI nor the database is the product — the product is a system whose seeing is remembered, questioned, and reported.

In your mind's eye: the Term 2 growth — employees, queries and reports that decide.

## Say it to your companion

Tell your companion, in your own words: The project separates two acts pupils confuse: **detection** — finding that a face is in the picture, and where — and **recognition** — saying whose it is. Detection is done with OpenCV's **Haar cascade**, a trained detector that scans the image for face patterns. What the camera sees is then **logged in an SQLite database** — a face_logs / attendance table of who was seen and when — because, as the book insists, **a database beats a text file**: the log can be queried, counted and kept honestly, not merely appended and forgotten. Term 2 grows the logger into a system: an **employees table linked to a face_log table** (the relational year's parent and child), Haar detection feeding the log, and **queries and reports that support decisions** — who was late how often, which door saw whom — finished as **PDF reports built with ReportLab**, the program itself printing its findings. The project's lesson is the integration: neither the AI nor the database is the product — the product is a system whose seeing is remembered, questioned, and reported. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Detection finds that a face is present and where; recognition says whose it is. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: OpenCV's Haar cascade. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: In an SQLite database — a face_logs / attendance table. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The log can be queried, counted and kept honestly. Do this with a real example of your own and write or say how you know it is right.
