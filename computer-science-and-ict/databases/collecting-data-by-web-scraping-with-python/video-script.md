# Video script — Collecting Data by Web Scraping with Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Web scraping** collects data by program: the program **requests** a page as a browser does, receives its HTML, and **extracts** the wanted pieces — the prices, names, results — from the page's structure into rows of a table. Indonesia's Grade 10 data chapter teaches it as the modern way data collection happens: not copying by eye, but describing the pattern once and letting the program harvest every page that matches. A scraper is only as honest as its pattern — it collects what the pattern says, including the page's errors.
The book's workbench is **Google Colab**, where Python runs in the browser with nothing installed. In it: **Beautiful Soup** parses the HTML and finds elements by their tags and classes; **pandas** holds the harvest as a DataFrame — rows and columns that can be cleaned, filtered and counted; **Plotly** turns the table into charts for the eye. The chapter's discipline travels with the tools: scrape only what may be taken (the site's terms and the law of data), record where each table came from, and validate the harvest before analysing it.
