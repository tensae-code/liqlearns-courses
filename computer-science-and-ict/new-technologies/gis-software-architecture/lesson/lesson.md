# GIS Software Architecture

## Do it first

Two GIS programs can draw the same map and be built completely differently inside. Rwanda's S1 teacher guide adds the architecture page — this lesson stands on it.

## Sub lesson 1 — Two architectures — project and database

The guide divides GIS software by **architecture**. A **project-oriented** system keeps one project's data in its **own files**, made for that project — simple, and hard to share. A **database-oriented** system keeps the geographic data in **one shared database** that many projects and users draw from — the data is stored once, kept consistent, and served to whoever is allowed. The trend the guide names is from projects toward the shared database.

In your mind's eye: two architectures — project and database.

## Sub lesson 2 — The RDBMS — the database under the map

The shared store is usually an **RDBMS — a relational database management system**: the same table-based engine that holds ordinary records, extended to hold **geometry** beside attributes. Features become **rows**, their facts **columns**, and the map and the table stay one thing — query the table and the map answers. Architecture matters because it decides **who can use the data, and whether everyone sees the same truth** (teacher guide — evidence).

In your mind's eye: the RDBMS — the database under the map.

## Say it to your companion

Tell your companion, in your own words: The guide divides GIS software by **architecture**. A **project-oriented** system keeps one project's data in its **own files**, made for that project — simple, and hard to share. A **database-oriented** system keeps the geographic data in **one shared database** that many projects and users draw from — the data is stored once, kept consistent, and served to whoever is allowed. The trend the guide names is from projects toward the shared database. The shared store is usually an **RDBMS — a relational database management system**: the same table-based engine that holds ordinary records, extended to hold **geometry** beside attributes. Features become **rows**, their facts **columns**, and the map and the table stay one thing — query the table and the map answers. Architecture matters because it decides **who can use the data, and whether everyone sees the same truth** (teacher guide — evidence). Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Project-oriented and database-oriented. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In its own files, made for that project. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: It is hard to share. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: In one shared database. Do this with a real example of your own and write or say how you know it is right.
