# E-Commerce

## Overview
This project is meant to be the back end for and e-commerce site that allows the user to make get, post, put, delete requests and communicate to a database.

### My goals are to...

* Allow the user to get all category, product, and tag data
* Allow user to make new category, product, and tag data
* Allow use to delete and edit all type of data
* Allow the use to drop a database and seed it

---

## Preview

![preview_one](https://user-images.githubusercontent.com/105886307/200938669-fd5e30ab-fac9-4ef2-ba12-b7f646868543.png)

![preview_two](https://user-images.githubusercontent.com/105886307/200938759-7153a75a-c5c4-435e-ab16-4f2630814abb.png)

To view a video demonstration of the application in action go [here](https://drive.google.com/file/d/1of3EFyMPKpcTBh-1ePypQvbyjo4XI91F/view)

---

## Installation

### To access this application...

* Install Node.js
* Install MySql
* Install Insomnia
* Clone this repository
* Change directory to this repository

---

## Usage

### How to set up the database...

1. Go to mysql in your terminal and and use the command 

```mysql
source db/schema.sql;
```

2. Then exit MySql and type npm run seed in your command line
```
npm run seed
```

### How to use the application...

1. Run npm start in the command line to start the server
2. Open up Insomnia
3. Create the desired routes and fill in the body with json if you are making a post or put request


