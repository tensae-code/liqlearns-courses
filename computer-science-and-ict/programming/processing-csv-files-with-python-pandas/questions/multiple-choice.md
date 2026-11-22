# Processing CSV Files with Python Pandas — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) What does `pd.read_csv("data.csv")` return?**
a) A picture of the table  b) A DataFrame holding the table  c) A printed page  d) A single number
**Answer: b) A DataFrame holding the table — The header becomes column names and each line a row, alive in memory.**

**2. (Sub lesson 1) In a DataFrame loaded from CSV, the column names come from —**
a) The file name  b) The first line of the file (the header)  c) The program’s author  d) The last line
**Answer: b) The first line of the file (the header) — That is why the formats lesson insists the header is never skipped.**

**3. (Sub lesson 2) Which line selects only the rows where the town is "Lyon"?**
a) df["Lyon"]  b) df.loc[df["town"] == "Lyon"]  c) df.max("Lyon")  d) print("Lyon")
**Answer: b) df.loc[df["town"] == "Lyon"] — loc with a condition keeps the rows where the condition is true.**

**4. (Sub lesson 2) A drone’s speed between two log rows is computed as —**
a) Altitude divided by time  b) Distance between the positions divided by the time between them  c) The number of rows divided by two  d) The maximum altitude
**Answer: b) Distance between the positions divided by the time between them — Speed is always distance over time; the log supplies both.**
