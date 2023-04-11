# CodeClan - Python Solo Project

<hr>

Python Travel is an app that allows users to track which countries and cities they would like to visit, and record the places they have already been.

<hr>

![name](https://github.com/Neil-Burgoyne/Python-Project/blob/main/homepage/Python%20Global%20Travel.png)

## Brief

Build an app to track someone's travel adventures.

### MVP

- The app should allow the user to track countries and cities they want to visit and those they have visited.
- The user should be able to create and edit countries
- Each country should have one or more cities to visit
- The user should be able to create and delete entries for cities
- The app should allow the user to mark destinations as visited or still to see

## Project Setup

<hr>

### Drops database:

```
dropdb python_travel
```

### Create Database:

```
createdb python_travel
```

```
psql -d python_travel -f db/python_travel.sql
```

### Runs the website on LocalHost

```
python3 -m flask run
```
