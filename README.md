# NoSQL in Action!

[![Build](https://github.com/w4bo/2023-nosql-utours/actions/workflows/build.yml/badge.svg)](https://github.com/w4bo/2023-nosql-utours/actions/workflows/build.yml)

Matteo Francia, University of Bologna.
Thanks to Enrico Gallinucci and Oscar Romero for sharing their teaching material.

Link to this repository: https://github.com/w4bo/2023-utours-nosql

## Teaching material

|          When           | Duration (hours) | What                                                                    |
|:-----------------------:|:----------------:|-------------------------------------------------------------------------|
| Mon 13/03/2023, 13:00   |         2        | Introduction to NoSQL databases with a focus on Document-based database |
| Tue 14/03/2023, 15:00   |         3        | Hands on MongoDB                                                        |
| Thu 16/03/2023, 08:15   |         2        | Introduction to property and knowledge graph databases                  |
| Thu 16/03/2023, 11:00   |         3        | Hands on Neo4J.                                                         |
| ~Fri 17/03/2023, 13:00~ |                  |                                                                         |
| Fri 24/03/2023, 13:00   |         1        | Final Test (~1 hour)                                                    |

- `code/` contains the software necessary to start the databases on docker
- `slides/` contains the teaching material

## Requirements

1. Install and run Docker Desktop and Studio3T
1. Clone the repository: `git clone https://github.com/w4bo/2023-utours-nosql.git`
1. Start the databases
    - On Windows, double click on `code/start.bat`
    - On Linux,
      ```sh
      cd code
      sh start-centos.sh
      ``` 
1. Connect Studio3T to MongoDB (`${MONGO_URL}:${MONGO_PORT}`, e.g. `127.0.0.1:27118`)
   ![immagine](https://user-images.githubusercontent.com/18005592/224693910-36e7fbd3-aac7-4888-8872-a3ef2f12bda1.png)
1. Access via browser the Neo4J's GUI (`${NEO4J_URL}:${NEO4J_PORT_GUI}`, e.g. `127.0.0.1:7474`)
