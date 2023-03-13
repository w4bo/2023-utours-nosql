# NoSQL in Action!

[![Build](https://github.com/w4bo/2023-nosql-utours/actions/workflows/build.yml/badge.svg)](https://github.com/w4bo/2023-nosql-utours/actions/workflows/build.yml)

Matteo Francia, University of Bologna.
Thanks to Enrico Gallinucci and Oscar Romero for sharing their teaching material.

## Teaching material

| Where |          When         | Duration (hours) | What                                                                    |
|:-----:|:---------------------:|:----------------:|-------------------------------------------------------------------------|
|  ???  | Mon 13/05/2023, 13:00 |         2        | Introduction to NoSQL databases with a focus on Document-based database |
|  ???  | Tue 14/05/2023, 15:00 |         3        | Hands on MongoDB                                                        |
|  ???  | Thu 16/05/2023, 13:00 |         2        | Introduction to property and knowledge graph databases                  |
|  ???  | Fri 17/05/2023, 13:00 |         3        | Hands on Neo4J. Final Test (~1 hour)                                    |

- `code/` contains the software necessary to start the databases on docker
- `slides/` contains the teaching material

## Requirements

1. Install and run Docker Desktop and Robo3T
1. Clone the repository: `git clone https://github.com/w4bo/2023-asw-nosql.git`
1. Double click on `code/start.bat` (on Windows)
1. Connect Robo3T to MongoDB (`${MONGO_URL}:${MONGO_PORT}`, e.g. `127.0.0.1:27018`)
1. Access via browser the Neo4J's GUI (`${NEO4J_URL}:${NEO4J_PORT_GUI}`, e.g. `127.0.0.1:7474`)