# Database-project

This is a 1-semester project for the course "Data Bases". It was carried out in collaboration with [Spyridonidis98](https://github.com/Spyridonidis98).  
It showcases the process of designing and constructing a database from scratch to be used by a scientific journal and article subscription service. It includes a bare-bones and minimalist, yet modern, clean and intuitive application for interacting with the Database.

## Features

- A fully working application for publishing journals and articles.
- User sign-in.
- Publisher sign-in.
- Publication of scientific magazines, issues of magazines, articles in each issue.
- A whole network of editors and authors, allowing for easy search between other works of the same person.
- Ability to rate an article.

## Technologies employed

- Python
- Tkinter
- SQLite
- Use of "prepared statements" for database security
- Appropriate use of indexes to enable handling millions of entries

## Entity – Relationship Diagram

![db](https://github.com/ChristoforosVlachos/Database-project/assets/96950242/879c37b3-720b-4e02-a0d7-0c87fe46662a)


## Screenshot

![db2](https://github.com/ChristoforosVlachos/Database-project/assets/96950242/1ee2c489-cb48-4c83-918c-82789196e39d)


## Try it!

After cloning the repository or downloading its contents, navigate inside the base folder and run "app.py". If you would prefer to create the database anew, run "create_database.py". You may also want to run "create_database_data.py"; this will insert some sample data into the database.
