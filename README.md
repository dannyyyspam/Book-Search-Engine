<h1 align="center">MERN Challenge: Book Search Engine</h1>

## Table of Contents

🔎

- [Description](#description)
- [User Story](#User-Story)
- [Acceptance Criteria](#Acceptance-Criteria)
- [Technology](#Technology)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contribution](#contribution)

## Description:

This application allows users to search for new books from Google's Book API. Users can log in to save the book they would like to purchase, as well as to remove the books from their library.

## User Story

👨‍💻

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

✅

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Technology:

🦾 <br>
Project is created with: <br>
![Technologies](https://img.shields.io/badge/-Node.js-339933?logo=Node.js&logoColor=white)
![Technologies](https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white)
![Technologies](https://img.shields.io/badge/-JavaScript-007396?logo=JavaScript&logoColor=white)

- MongoDB
- Express.js
- React.js
- GraphQL API
- Apollo Server

## Installation

💾 <br>
To run this project, install it locally using npm:

```
npm install
```

## Usage

💻 <br>
After installing npm packages, the application will be invoked by using the following command:

```
npm run develop
```

#### Heroku Deployment

[Click me to see app!]()

- Create heroku app

  ```
  heroku create
  ```

- Create database on MongoDB Atlas:

  ```
  Cluster ➡️ Collections ➡️ Create Database
  ```

- Change Heroku setting

  ```
  Config Vars ➡️ KEY: MONGODB_URI ➡️ VALUE: (from Cluster connect, change password and database name)
  ```

- Git push
  ```
  git push heroku main
  heroku open
  ```

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <br>
This project is licensed under MIT, for more information please visit [this website](https://opensource.org/licenses/MIT)

## Contribution

:octocat: [Daniel A](https://github.com/dannyyyspam)
