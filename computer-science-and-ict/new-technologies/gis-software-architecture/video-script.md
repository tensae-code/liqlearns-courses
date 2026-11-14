# Video script — GIS Software Architecture

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The guide divides GIS software by **architecture**. A **project-oriented** system keeps one project's data in its **own files**, made for that project — simple, and hard to share. A **database-oriented** system keeps the geographic data in **one shared database** that many projects and users draw from — the data is stored once, kept consistent, and served to whoever is allowed. The trend the guide names is from projects toward the shared database.
The shared store is usually an **RDBMS — a relational database management system**: the same table-based engine that holds ordinary records, extended to hold **geometry** beside attributes. Features become **rows**, their facts **columns**, and the map and the table stay one thing — query the table and the map answers. Architecture matters because it decides **who can use the data, and whether everyone sees the same truth** (teacher guide — evidence).
