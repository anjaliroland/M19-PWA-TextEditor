# Progressive Web Applications (PWA): Text Editor [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


## Table of Contents

- [Description](#📝-description)
    - [User Story](#👤-user-story)
    - [Acceptance Criteria](#☑️-acceptance-criteria)
- [Technologies Used](#🛠️-technologies-used)
- [Usage](#💻-usage) 
    - [Screenshot](#📸-screenshot)
- [License](#📃-license)
- [Links](#🔗-links)

--------------------

## 📝 Description

For Module #19 we were tasked with adding to starter code to create a text-editor that runs in the browser and can be installed as a PWA for offline use. By using the class activities and class recordings as references I was able to build a deployed app that meets the below criteria.


### 👤 User Story


```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### ☑️ Acceptance Criteria

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

---------------

## 🛠️ Technologies Used

<ul>
<li>JavaScript
<li>idb
<li>WebpackPwaManifest
<li>Heroku
</ul>

-----------------

## 💻 Usage

By clicking on the link at the bottom of the readme, you can imediately start adding text snippets and using the app in the browser or hit 'install' to download the PWA to use it later.

### 📸 Screenshot

![screenshot of deployed app](./assets/images/screenshot.jpeg)

----------------


## 📃 License 

Please refer to the LICENSE in the repo.

---------------

##  🔗 Links 

Deployed Application: https://another-note-taker-0303027f81b2.herokuapp.com/

