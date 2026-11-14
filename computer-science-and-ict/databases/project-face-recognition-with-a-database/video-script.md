# Video script — Project — Face Recognition with a Database

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The project separates two acts pupils confuse: **detection** — finding that a face is in the picture, and where — and **recognition** — saying whose it is. Detection is done with OpenCV's **Haar cascade**, a trained detector that scans the image for face patterns. What the camera sees is then **logged in an SQLite database** — a face_logs / attendance table of who was seen and when — because, as the book insists, **a database beats a text file**: the log can be queried, counted and kept honestly, not merely appended and forgotten.
Term 2 grows the logger into a system: an **employees table linked to a face_log table** (the relational year's parent and child), Haar detection feeding the log, and **queries and reports that support decisions** — who was late how often, which door saw whom — finished as **PDF reports built with ReportLab**, the program itself printing its findings. The project's lesson is the integration: neither the AI nor the database is the product — the product is a system whose seeing is remembered, questioned, and reported.
