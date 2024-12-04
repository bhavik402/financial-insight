- [CLI App](#cli-app)
    - [Core Features](#core-features)
    - [UI Design for CLI](#ui-design-for-cli)
- [ETL App](#etl-app)
    - [Core Features](#core-features-1)
- [REST API](#rest-api)
    - [Core Features](#core-features-2)
- [Web App](#web-app)
      - [Options](#options)


# CLI App

> Used for reading CSV files directly and printing out report by year

### Core Features

- Pass a year via command line argument
  - Based on this year print report for Year To Date report first, and than for each month in DESC order
    - For example, for 2024, report YTD for 2024 and Dec, Nov, Oct, etc. 
- Technical Info
  - Read info from each statement from different institutions 
  - Compile information and transform it into and single "internal model" that can be used to run logic agains

### UI Design for CLI 



# ETL App

> Used for reading CSV files and inserting them into database with specific data model. This will be used by REST API to serve a frontend app in the future

###  Core Features

- read all statements csv files and transform them into database tables



# REST API 

> Basically a CRUD api, to serve data from database that was populated by ETL app

###  Core Features

- create rest api that allows CRUD ops 



# Web App

> Build a web app, to view data via REST API


--- 

#### Options
  - [ ] Go
    - [ ] CLI App: Standard Lib
    - [ ] ETL App: Standard Lib 
    - [ ] API: Standard Lib/Gin?
  - [ ] Python
    - [ ] CLI App: Standard Lib
    - [ ] ETL App: Standard Lib 
    - [ ] API: Django REST 
  - [ ] Java
    - [ ] CLI App: Standard Lib
    - [ ] ETL App: Standard Lib 
    - [ ] API: Spring Boot 
  - [ ] Typescript with Node, API: 
    - [ ] CLI App: Standard Lib
    - [ ] ETL App: Standard Lib 
    - [ ] API: NestJS 
