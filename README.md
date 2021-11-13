# WILDLIFE ANIMALS TRACKER

## Project Author:
CARLOS KIPKOECH

## Project Description
It's An Application that allows rangers to sight animals, record their location and condition if endangered.

## Technologies Used
* Java
* POSTGRES
* Spark
* Gradle
* JUnit

### SetUp link:
Deployed to: [Heroku]().
Also you can,
* Clone repository
* Locally in PSQL setup the database as follows;

* CREATE DATABASE wildlife_tracker;
* Connect to the database : \c wildlife_tracker;
* Create the following tables in wildlife_tracker
* CREATE TABLE endangered_animals (id serial PRIMARY KEY, name varchar, health varchar, age varchar);
* CREATE TABLE sightings (id serial PRIMARY KEY, animal_id int, location varchar, ranger_name varchar);
* CREATE TABLE animals (id serial PRIMARY KEY, name varchar, health varchar, age varchar);
* CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;


* In your terminal type "gradle run" inside project directory
* Open a tab in your computer and launch 'http://localhost:4567'


### Usage
To monitor Wildlife.

