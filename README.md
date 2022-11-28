# Module 19 Text Editor

![badge](https://img.shields.io/badge/license-MIT-brightgreen)

## Description

This is a progressive web application (PWA) which is a text editor. This application has the following features:

- Follows the client and server folder structure
- To run the application, enter `npm run start` and the application will launch the backend server
- In the browser, navigate to `localhost:3000` to view and interact with the application
- The user can add text into the text editor and if the browser is closed and reopened, the text will still be shown in the browser
- When webpack is run, the html file, service worker, and manifest files are created
- In the browser, when the user clicks the `Install!` button, the application is downloaded as an icon on the desktop
- This application has also been deployed to Heroku

## Project Links

- https://ancient-spire-48164.herokuapp.com/
- https://github.com/iamjoyfulgirl/module-19-text-editor

## Table of Contents

- [Installation](#installation)
- [Questions](#questions)

## Installation

`npm run start`

## Usage

Use this just like any text editor

## Screenshots of Application

### App in Browser:

![in browser](./Assets/JATE%20web%20app%20in%20browser.png)

### Install Prompt:

![install prompt](./Assets/JATE%20install%20prompt.png)

### Installed App Icon on Desktop:

![install icon](./Assets/Installed%20apps%20icon%20on%20desktop.png)

### Installed PWA App:

![PWA](./Assets/PWA%20installed%20app.png)

# Acceptance Criteria

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

## Questions?

Questions about this project can be directed to:

- Email: sherri.a.knight@gmail.com
- You can view more of my projects at https://github.com/iamjoyfulgirl

---

Module 19 Text Editor - Copyright 2022 Sherri Knight
