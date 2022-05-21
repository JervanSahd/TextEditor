# Text Editor Progressive Web Applications (PWA):

A developer can create notes or code snippets with or without an internet connection and can reliably retrieve them for later use.

## Description

A text editor that runs in the browser. The app is be a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline. It implement methods for getting and storing data to an IndexedDB database. It uses a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

This full-stack application is deployed to Heroku using the [Heroku Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide).

## Acceptance Criteria

```md
- Open application in editor and see a client server folder structure

- Run `npm run start` from the root directory and find application will start up the backend and serve the client

- Run the text editor application from terminal and JavaScript files have been bundled using webpack

- Run webpack plugins and generated HTML file, service worker, and a manifest file

- Use next-gen JavaScript in application the text editor still functions in the browser without errors

- Open the text editor the IndexedDB has immediately created a database storage

- Enter content and subsequently click off of the DOM window and find that the content in the text editor has been saved with IndexedDB

- Reopen the text editor after closing it the content in the text editor has been retrieved from our IndexedDB

- Click on the Install button and downloaded web application as an icon on my desktop

- Load my web application a registered service worker using workbox

- Register a service worker and have a static assets pre cached upon loading along with subsequent pages and static assets

- Deploy to Heroku have proper build scripts for a webpack application
```

## Review

You are required to submit the following for review:

- The URL of the deployed application

https://text-editor-pwa-ss.herokuapp.com/

- The URL of the GitHub repository, with a unique name and a README describing the project

https://github.com/JervanSahd/TextEditor

---
