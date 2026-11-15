# IT125 Database Design Project: Tree Frog Movie Database

This repository houses the documentation, relational schema models, and SQL scripts for our **IT 125** quarterly database design project.

---

## 🐸 Project Overview
The **Tree Frog Movie Database** is a centralized relational information system engineered to catalog and connect data across the film industry—linking movies, cast and crew, awards, genres, soundtracks, and user reviews. Designed to serve general audiences, film critics, producers, and casting directors, this system eliminates redundant data entry, streamlines talent and media discovery, and supports data-driven insights into film trends and production success.

---

## 🛠️ Technologies Used
* **Database Engine:** MySQL
* **Modeling & Administration:** MySQL Workbench
* **Development Environment:** Built on macOS 26.6.2 (and synced via Git/VS Code)

---

## ✨ Key Database Features
* **Comprehensive Film Cataloging:** Manages core movie metadata including release years, filming locations, trailers, genres, awards, and soundtracks.
* **Cast & Crew Biographies:** Stores centralized profiles for actors, directors, producers, and writers—tracking birth dates, ages, birthplaces, headshots, demo reels, and career histories.
* **Cross-Referenced Filmographies:** Enables instant lookup of all films associated with any actor, director, producer, or writer.
* **Awards & Recognition Tracking:** Records honors and nominations (such as Oscars) won by specific films and individuals, organized by category and year.
* **Genre & Soundtrack Indexing:** Categorizes titles across genres (Action, Comedy, Horror, Animated, Superhero, etc.) and links soundtracks and musical scores directly to films.
* **Ratings & Community Reviews:** Supports structured critic evaluations and audience feedback to aid viewing decisions and measure reception.
* **Relational Integrity & Decision Support:** Minimizes duplicate records through normalized table relationships while helping producers and casting directors evaluate talent histories and project success factors.

---

## 📐 Database Design
* An **Enhanced Entity-Relationship (EER)** diagram illustrating table structures, primary/foreign keys, and cardinality is included in the repository.

---

## 📂 Project Structure
```text
IT125_Movie_Database/
├── design/     # Entity-Relationship Diagrams (ERDs), EER models, and schema blueprints
├── docs/       # Project requirements, written reports, and supporting documentation
├── sql/        # SQL scripts for schema creation, data population, and queries
└── README.md   # Project summary and repository guide