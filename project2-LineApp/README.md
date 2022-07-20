<div align="center">
    <img 
        alt="project2-LineApp_main"
        width="250px"
        src="https://github.com/carlos-garcia-dev/Ironhack-Bootcamp-Images/blob/main/project2-LineApp/LineApp_logo.png" />
</div>
<div align="center">
  <h1>LineApp - Module 2</h1>
  <strong>Full-stack music plattform for streamings and events</strong>
</div>

</br>

## Introduction

The main idea at the creation of this application was to build a service for musical events so as it could be used as reference by the user to attend music performances and support their favourite artists.

![project2-LineApp_main](https://github.com/carlos-garcia-dev/Ironhack-Bootcamp-Images/blob/main/project2-LineApp/LineApp_00.jpg)

It was the _second project_ of the bootcamp and it was made at the end of the second module. The website it is basically a _CRUD Full-Stack app_ with _conditional rendering_, _noSQL database_ with _multiple and populated collections_ and a _remote database_.

- The **back-end** had multiple routes and endpoints sustained with no-SQL database. The main libraries and tools for this project was: _ExpressJS_, _Mongoose_, _MongoDB_, _MongoAtlas_ or _Passport_ or among others.

- The **front-end** was created with _Bootstrap_ and _Handlebars_ including conditional rendering due to authentication. Also, it was implemented features like _Google Maps_ embedding so the potential attendants could see if a music event it is celebrated near them. The tools or libraries for this project were: _Bootstrap_, _Handlebars_ or _Heroku_.

The website had _authentication service_ and different roles according to the relation chosen by the user and it had features like: _creating_, _saving_, _editing_ or _deleting_ events.

When we realized that during the confinment appeared many streamed concerts or events we thought it was a good idea to develope a service so as user could save them in order to continue supporting their favourite artists. We found very appropiate to create a plattform where: users, artists and promoters could be benefited or subsist during that exceptional times.

- The project was made by _Maria Luisa Santos_ and _Carlos García_.

## Technologies

<section align="center" sytle="padding-top: 20%">
    <img align="left"   style="float: left; margin-right: 2px;" alt="MongoDB" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/01.MongoDB.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Express" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/02.Express.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="ReactJS" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/03.ReactJS.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="NodeJS" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/04.NodeJS.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="JavaScript" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/05.JavaScript.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="HTML5" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/06.HTML5.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="CSS3" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/07.CSS3.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Git" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/17.Git.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Handlebars" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/16.Handlebars.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Bootstrap" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/08.Bootstrap.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Heroku" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/21.Heroku.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="GitHub" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/18.GitHub.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Visual Studio Code" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/19.VSCode.png" />
    <img align="left"   style="float: left; margin-right: 4px;" alt="Terminal" width="48px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/20.Terminal.png" />
</section>

</br>

## Project

One of the _pain points_ of the project was the creation of the building a clear and solid database so it could be easily accessed for all the different three roles: user, partner and admin.

## Routes

### Guest

| Method  | Path        | Description   |
| :-----: | ----------- | ------------- |
| **Get** | /           | Main page     |
| **Get** | /events/    | Event list    |
| **Get** | /events/:id | Event details |

### Client

|  Method  | Path     | Description  |
| :------: | -------- | ------------ |
| **Get**  | /signup  | Registration |
| **Post** | /signup  | Registration |
| **Get**  | /login   | Access       |
| **Post** | /login   | Access       |
| **Get**  | /profile | Saved events |

### Partner

|  Method  | Path                       | Description        |
| :------: | -------------------------- | ------------------ |
| **Get**  | /partner/signup            | Registration       |
| **Post** | /partner/signup            | Registration       |
| **Get**  | /partner/login             | Access for partner |
| **Post** | /partner/login             | Access for partner |
| **Get**  | /partner/event-list        | Event list         |
| **Get**  | /partner/event-list/edit   | Edit events        |
| **Post** | /partner/event-list/edit   | Edit events        |
| **Get**  | /partner/event-list/delete | Delete events      |

### Admin

| Method  | Path                | Description        |
| :-----: | ------------------- | ------------------ |
| **Get** | /management         | Access             |
| **Get** | /management/client  | Client management  |
| **Get** | /management/partner | Partner management |

## Archives organization

```bash
│
├── 📁 bin
│   ├── clients-collection.json
│   ├── events-collection.json
│   ├── seed.js
│   └── www
├── 📁 configs
│   ├── debugger.config.js
│   ├── locals.config.js
│   ├── middleware.config.js
│   ├── mongoose.config.js
│   ├── passport.config.js
│   ├── preformatter.config.js
│   └── views.configs.js
├── 📁 models
│   ├── client.model.js
│   └── event.model.js
├── package-lock.json
├── package.json
├── 📁 public
│   ├── 📁 images
│   ├── 📁 javascripts
│   │   ├── map.js
│   │   ├── script.js
│   │   └── styles.js
│   └── 📁 stylesheets
│       ├── style.css
│       ├── style.css.map
│       └── style.scss
├── 📁 routes
│   ├── api.routes.js
│   ├── base.routes.js
│   ├── client.routes.js
│   ├── guest.routes.js
│   ├── index.js
│   └── partner.routes.js
└── 📁 views
    ├── 📁 admin
    │   ├── client.hbs
    │   ├── index.hbs
    │   ├── login.hbs
    │   └── partner.hbs
    ├── 📁 client
    │   ├── index.hbs
    │   ├── login.hbs
    │   ├── private.hbs
    │   ├── profile.hbs
    │   └── signup.hbs
    ├── error.hbs
    ├── index.hbs
    ├── layout.hbs
    ├── 📁 main
    │   ├── about.hbs
    │   ├── event-details.hbs
    │   ├── event-edit.hbs
    │   ├── event-list.hbs
    │   ├── event-new.hbs
    │   └── streaming.hbs
    ├── not-found.hbs
    └── 📁 partner
        ├── about.hbs
        ├── index.hbs
        ├── login.hbs
        ├── private.hbs
        └── signup.hbs
```

## Installation

1. Clone or download the repository
2. Install the dependencies: `npm i`
3. Open the archive: `app.js`
