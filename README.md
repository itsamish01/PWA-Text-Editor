
  # Text Editor (PWA)
  
  Link to deployed application => https://super-cool-pwa-text-editor.herokuapp.com/
  
  ## Table of Contents
- [Description](#description)

- [Installation](#installation)

- [Usage](#usage)

- [Contributors](#contributors)

- [Testing](#testing)

- [License](#license)

- [Questions](#questions)

  ## Description
  PWA Text Editor is a versatile app that allows users to write and save text both online and offline. It utilizes various data persistence options, including indexedDB and local storage, to ensure that data is always accessible and not lost in any scenario. This application is ideal for developers who need a scratch pad for jotting down code snippets and coding ideas. Users can download the app to their desktop and access it as an application, even when offline. With PWA Text Editor, you can write, edit, and save your work with ease, knowing that your data is secure and accessible at all times.

  ## User Story

  AS A developer
  
  I WANT to create notes or code snippets with or without an internet connection
  
  SO THAT I can reliably retrieve them for later use
  
  ## Acceptance Criteria
  GIVEN a text editor web application
* WHEN I open my application in my editor
* THEN I should see a client server folder structure
* WHEN I run `npm run start` from the root directory
* THEN I find that my application should start up the backend and serve the client
* WHEN I run the text editor application from my terminal
* THEN I find that my JavaScript files have been bundled using webpack
* WHEN I run my webpack plugins
* THEN I find that I have a generated HTML file, service worker, and a manifest file
* WHEN I use next-gen JavaScript in my application
* THEN I find that the text editor still functions in the browser without errors
* WHEN I open the text editor
* THEN I find that IndexedDB has immediately created a database storage
* WHEN I enter content and subsequently click off of the DOM window
* THEN I find that the content in the text editor has been saved with IndexedDB
* WHEN I reopen the text editor after closing it
* THEN I find that the content in the text editor has been retrieved from our IndexedDB
* WHEN I click on the Install button
* THEN I download my web application as an icon on my desktop
* WHEN I load my web application
* THEN I should have a registered service worker using workbox
* WHEN I register a service worker
* THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
* WHEN I deploy to Heroku
* THEN I should have proper build scripts for a webpack application

  ## Installation
  To get started with this project, simply clone the repository and run the command "npm install". This will automatically install all the required dependencies as they are defined in the package.json file.

  ## Usage
  To start using this application, you can simply open it up in your browser by accessing the deployed app link provided at the top of this readme file. Once the page has loaded, you can start using the text editor right away.

  If you want to use the app offline, you can still access it through the link and then click the "install" button located at the top left corner of the page. This will install the application on your device so you can access it even without an internet connection.
  
  
  ## License
  ISC
 
