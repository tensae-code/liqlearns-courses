# Processing CSV Files with Python Pandas

## Do it first

Here is a CSV file printed on paper: twenty rows of weather readings — date, town, temperature, rain. Answer three questions by hand: which day was hottest? How many days had rain in one chosen town? What was the average temperature? Time yourself; it is slow, error-prone work. Now imagine the file has not twenty rows but two hundred thousand, as real data files do. Keep your answers and your time — the lesson shows the library that loads the whole file in one line and answers each question with one line more.

## Sub lesson 1 — Reading a CSV table with pandas

**pandas** is Python’s data library, and its front door is one line: `pd.read_csv("readings.csv")`. The file — the plain-text table of the formats lesson — becomes a **DataFrame**, a table living in the program’s memory. The header line gives the **column names**; every other line is a **row**, its values already placed under their names and, where the file allows, already understood as numbers or dates rather than text. From there the program can ask the table about itself: show the first rows to check the loading, count the rows, list the columns. Two hundred thousand rows load as calmly as twenty — that calm is the point of the library: the table is data the program can compute on, not text it must re-read for every question.

[Picture — a CSV file on the left flowing through the read_csv arrow into a neat table grid on the right, its header becoming column names]

## Sub lesson 2 — Asking questions of the table — and a real flight log

Questions become selections and calculations. **Selecting rows** uses `loc` with a condition: `df.loc[df["town"] == "Lyon"]` keeps only Lyon’s rows; conditions combine — a town and a temperature above a value. **Taking a column** is naming it: `df["temperature"]`. On a column, the library computes in one call: the maximum for the hottest day, the mean for the average, a count of the rows that passed a test for the rainy days. Each of your hand-answered questions from Do it first is now one line — and the same lines work unchanged on the two-hundred-thousand-row file.

The SNT book’s second CSV is wilder: a **drone’s flight log** — row after row of time, latitude, longitude, altitude recorded during a real flight. The same pandas moves apply: load it, select, compute — and with positions and times in hand, the distance between successive points divided by the time between them gives the drone’s **speed** along its path, ready to draw on a map. Data is data: the weather table and the flight log are the same craft.

[Picture — a drone’s curved flight path over fields, with three log rows beneath it and the speed worked out between two of the points]

## Say it to your companion

Tell your companion, in your own words: pandas reads a CSV into a DataFrame in one line — header to column names, lines to rows — and then loc selects rows by condition and the library computes maxima, means and counts in one call, on twenty rows or two hundred thousand. Take one question about the printed CSV and say its pandas line aloud as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: load a CSV file into a pandas DataFrame and report its columns and row count. Do this with a real example of your own — in a real Python program with pandas, on a CSV file of your own or the lesson’s — and write or say how you know it is right.
2. Show it, don't just say it: select the rows of a DataFrame that match a condition, using loc. Do this with a real example of your own — in a real Python program with pandas, on a CSV file of your own or the lesson’s — and write or say how you know it is right.
3. Show it, don't just say it: compute a maximum, a mean and a count on a chosen column. Do this with a real example of your own — in a real Python program with pandas, on a CSV file of your own or the lesson’s — and write or say how you know it is right.
4. Show it, don't just say it: explain how a drone’s speed is computed from the rows of its flight log. Do this with a real example of your own — in a real Python program with pandas, on a CSV file of your own or the lesson’s — and write or say how you know it is right.
