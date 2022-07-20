<div align="center">
    <img 
        alt="project3-DotEnv_main"
        width="200px"
        src="https://github.com/carlos-garcia-dev/Ironhack-Bootcamp-Images/blob/main/project3-DotEnv/DotEnv_logo.png" />
</div>
<div align="center">
  <h1>DotEnv - Module 3</h1>
  <strong>Single Page Application blog about technology including a CRUD and a noSQL database</strong>
</div>

</br>

## Introduction

The project was a blog focused on knowledge sharing between different disciplines of technology: web-development, data-science, UX/UI design and cybersecurity. It was the third project of the Bootcamp of a _SPA Full-stack_ blog CRUD including a noSQL database and different roles and populated collections.

<!-- <img /> -->

- The **back-end** was made with the development of an _API Rest_ with multiple routes and endpoints for a remote no-SQL database. The main libraries and tools for this project was: _ExpressJS_, _Mongoose_, _MongoDB_, _Multer_, _Passport_ or _Cloudinary_ among others.

- On the other side, the **front-end** was created with _React JS_ including conditional rendering due to authentication. The structure of the project was focused in React components trying to reach atomic-design to ensure scalability. The tools or libraries for this project were: _Axios_, _Bootstrap_, _Heroku_ or _React_.

- The blog had _authentication_ and different roles according to the discipline chosen by the user and it was implemented features like: _creating_, _saving_, _editing_ or _deleting articles or comments_ so the users could share their thoughts or build relations.

As soon as I realized that it was a lot of ignorance between the projects of different bootcamps despite of sharing a common field; I thought it was a beneficial to build a plattform to make an approach between these fields.
The project was made by _Carlos García_.

## Technologies

<section align="center" sytle="padding-top: 20%; padding-bottom: 20%">
    <img align="left"   style="float: left; margin-right: 2px;" alt="MongoDB" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/01.MongoDB.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Express" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/02.Express.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="ReactJS" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/03.ReactJS.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="NodeJS" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/04.NodeJS.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="JavaScript" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/05.JavaScript.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="HTML5" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/06.HTML5.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="CSS3" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/07.CSS3.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Git" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/17.Git.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Postman" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/22.Postman.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="SaSS" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/15.SaSS.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Bootstrap" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/08.Bootstrap.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Heroku" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/21.Heroku.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="GitHub" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/18.GitHub.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Visual Studio Code" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/19.VSCode.png" />
    <img align="left"   style="float: left; margin-right: 4px;" alt="Terminal" width="40px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/20.Terminal.png" />
</section>

</br>

## Project

It was crucial for the development to maintain a simple components so as they could be reused or accessed easily. I found that it was one of the most important tasks to maintain an efficient and clear state with React. Besides, the time management gained more importance while working individually.

## Endpoints

### Authenticated

|  Method  | Path     | Description   |
| :------: | -------- | ------------- |
| **Post** | /signup  | Register User |
| **Post** | /signin  | Log in User   |
| **Post** | /signout | Sign Out      |

### Commentaries

|   Method   | Path               | Description          |
| :--------: | ------------------ | -------------------- |
|  **Get**   | /getAllComments    | Get all comments     |
|  **Get**   | /getOneComment/:id | Get specific comment |
|  **Put**   | /editComment/:id   | Edit comment         |
|  **Post**  | /newComment        | Create new comment   |
| **Delete** | /deleteComment/:id | Delete comment       |

### Files

|  Method  | Path    | Description   |
| :------: | ------- | ------------- |
| **Post** | /upload | Upload images |
| **Post** | /avatar | Upload avatar |

### Publication

|   Method   | Path                        | Description          |
| :--------: | --------------------------- | -------------------- |
|  **Get**   | /getAllPublications         | Get all comments     |
|  **Get**   | /getOnePublication/:id      | Get specific comment |
|  **Get**   | /getPublicationComments/:id | Get specific comment |
|  **Post**  | /newPublication             | Create new comment   |
|  **Put**   | /editPublication/:id        | Edit comment         |
| **Delete** | /deletePublication/:id      | Delete comment       |

### User

|   Method   | Path            | Description        |
| :--------: | --------------- | ------------------ |
|  **Get**   | /getAllUsers    | Access             |
|  **Get**   | /getOneUser/:id | Client management  |
|  **Put**   | /editUser/:id   | Partner management |
| **Delete** | /deleteUser/:id | Partner management |

---

## Archives organization

### Client

```bash
│
├── 📁 client
│   ├── README.md
│   ├── package-lock.json
│   ├── package.json
│   ├── 📁 public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   └── 📁 src
│       ├── 📁 components
│       │   ├── App.css
│       │   ├── App.js
│       │   ├── 📁 layout
│       │   │   ├── 📁 footBar
│       │   │   │   ├── FootBar.css
│       │   │   │   └── FootBar.js
│       │   │   └── 📁 navBar
│       │   │       ├── NavBar.css
│       │   │       ├── NavBar.js
│       │   │       └── logo.png
│       │   ├── 📁 pages
│       │   │   ├── 📁 about
│       │   │   │   └── About.js
│       │   │   ├── 📁 becomeUser
│       │   │   │   └── BecomeUser.js
│       │   │   ├── 📁 commentary
│       │   │   │   ├── 📁 card
│       │   │   │   │   └── CommentaryCard.js
│       │   │   │   └── 📁 form
│       │   │   │       └── CommentaryForm.js
│       │   │   ├── 📁 main
│       │   │   │   └── Main.js
│       │   │   ├── 📁 publication
│       │   │   │   ├──📁  create
│       │   │   │   │   └── PublicationCreate.js
│       │   │   │   ├── 📁 details
│       │   │   │   │   └── PublicationDetails.js
│       │   │   │   └── 📁 list
│       │   │   │       ├── PublicationList.js
│       │   │   │       ├── PublicationListCard.css
│       │   │   │       └── PublicationListCard.js
│       │   │   └── 📁 user
│       │   │       ├── 📁 profile
│       │   │       │   ├── UserProfile.js
│       │   │       │   ├── UserProfileForm.css
│       │   │       │   ├── UserProfileForm.js
│       │   │       │   └── UserSavedPublications.js
│       │   │       ├── 📁 signIn
│       │   │       │   └── UserSignIn.js
│       │   │       └── 📁 signUp
│       │   │           └── UserSignUp.js
│       │   └── 📁 shared
│       │       ├── 📁 alert
│       │       │   ├── Alert.js
│       │       │   └── logo.png
│       │       ├── 📁 loader
│       │       │   ├── Loader.css
│       │       │   └── Loader.js
│       │       └── 📁 modal
│       │           └── Modal.js
│       ├── index.js
│       └── 📁 service
│           ├── auth.service.js
│           ├── commentary.service.js
│           ├── file.service.js
│           ├── publication.service.js
│           └── user.service.js
├── package-lock.json
└── package.json
```

### Server

```bash
│
└── 📁 server
    ├── app.js
    ├── 📁 bin
    │   ├── publications-collection.json
    │   ├── seed.js
    │   ├── users-collection.json
    │   └── www
    ├── 📁 configs
    │   ├── cloudinary.config.js
    │   ├── cors.config.js
    │   ├── debugger.config.js
    │   ├── middleware.config.js
    │   ├── mongoose.config.js
    │   └── passport.config.js
    ├── 📁 middlewares
    │   └── middlewares.js
    ├── 📁 models
    │   ├── commentary.model.js
    │   ├── publication.model.js
    │   └── user.model.js
    ├── package-lock.json
    ├── package.json
    └── 📁 routes
        ├── auth.routes.js
        ├── commentary.routes.js
        ├── file.routes.js
        ├── index.js
        ├── publication.routes.js
        └── user.routes.js
```

## Installation

1. Clone or download the repository
2. Install the dependencies: `npm i`
3. Open the archive: `app.js`
