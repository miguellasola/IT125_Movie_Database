# Movie Database Design Project

## Database Design Explanation
This relational database is designed to store and organize comprehensive film, cast, user review, and award data. To maintain Third Normal Form (3NF) and eliminate data redundancy, core entities (`MOVIES`, `PEOPLE`, `GENRES`, `AWARDS`, and `USERS`) are separated from transactional and associative records. 

Because movies frequently belong to multiple genres and involve numerous cast and crew members, many-to-many ($M:M$) relationships were resolved using dedicated bridge tables (`MOVIE_GENRES`, `MOVIES_CREDITS`, and `AWARDS_RECIPIENTS`). A key design challenge was modeling credits where individuals hold specific roles or play distinct characters, as well as supporting both movie-level and individual-level awards. This was solved by adding `role_type` and nullable `character_name` attributes to `MOVIES_CREDITS`, ensuring referential integrity through strict primary and foreign key constraints across all tables.