# :seedling: [Food Miles](https://food-miles-fac17.herokuapp.com/) :seedling:

---

As a user, I need an easy way to find out how local my shopping list is by comparing supermarkets and where they source their food from.
![](https://media.giphy.com/media/yaxcIHO5OgP4Y/giphy.gif)

---

[![Build Status](https://travis-ci.com/fac-17/FFFF.svg?branch=master)](https://travis-ci.com/fac-17/FFFF)
[![codecov](https://codecov.io/gh/fac-17/FFFF/branch/master/graph/badge.svg)](https://codecov.io/gh/fac-17/FFFF)
[![Dependencies](http://img.shields.io/david/fac-17/FFFF.svg?style=flat)](https://david-dm.org/fac-17/FFFF)
[![Known Vulnerabilities](https://snyk.io//test/github/fac-17/FFFF/badge.svg?targetFile=package.json)](https://snyk.io//test/github/fac-17/FFFF?targetFile=package.json)
![Heroku](https://heroku-badge.herokuapp.com/?app=foodmiles)

## Tech Stack
1. NodeJS + ExpressJS
2. PostgreSQL
3. HandlebarsJS
4. SASS
5. Testing with tape, tap-spec and supertest
6. CI with Travis CI
7. Deployment on Heroku

## Getting Started

### Installing

A step by step series of examples that tell you how to get a development env running

```
npm install
```
Create a .env file and paste your database links there:
```
TEST_DATABASE_URL=yourPostgreSQLTestingLink
DATABASE_URL=yourPostgreSQLLink
```
```
npm run db_init
npm run lint
npm test
npm run watch
```
## Screenshots & Audits
![](https://i.imgur.com/LrD7pCn.png)
![](https://i.imgur.com/ltjhniA.png)

## Authors

- [Andy](https://github.com/andy-mc-donald)
- [Gigi](https://github.com/gminova)
- [Jack](https://github.com/jackbridger)
- [Jan](https://github.com/crianonim)



## What we Learned

### Jan
 
#### 11/09 Wed

- REFERENCES in postgres does not imply NOT NULL
- app.render does not send response but in callback  (err,html)=>{} provides string so can be used maybe in testing

#### 16/09 MOn
- to refer to a global variable in handlebars when you are in #each use ../variableName
#### 18/09 Wed
```css
.text {
    position: absolute;  
    left: 50%;                        /* horizontal alignment */
    top: 50%;                         /* vertical alignment */
    transform: translate(-50%, -50%); /* precise centering; see link below */
}
```

Icon attribution:

<div>Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/"             title="Flaticon">www.flaticon.com</a></div>