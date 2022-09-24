# Text Editor PWA

This project is a single page text editor that runs in the browser.  

## Table Of Contents

 [User Story](#user-story)</br>
 [Project Criteria](#project-criteria)</br>
 [Installation](#installation)
 [Preview](#preview)</br>
 [Questions](#questions)</br>

## User Story

AS A developer</br>
I WANT to create notes or code snippets with or without an internet connection</br>
SO THAT I can reliably retrieve them for later use

## Project Criteria

GIVEN a text editor web application</br>
WHEN I open my application in my editor</br>
THEN I should see a client server folder structure</br>
WHEN I run `npm run start` from the root directory</br>
THEN I find that my application should start up the backend and serve the client</br>
WHEN I run the text editor application from my terminal</br>
THEN I find that my JavaScript files have been bundled using webpack</br>
WHEN I run my webpack plugins</br>
THEN I find that I have a generated HTML file, service worker, and a manifest file</br>
WHEN I use next-gen JavaScript in my application</br>
THEN I find that the text editor still functions in the browser without errors</br>
WHEN I open the text editor</br>
THEN I find that IndexedDB has immediately created a database storage</br>
WHEN I enter content and subsequently click off of the DOM window</br>
THEN I find that the content in the text editor has been saved with IndexedDB</br>
WHEN I reopen the text editor after closing it</br>
THEN I find that the content in the text editor has been retrieved from our IndexedDB</br>
WHEN I click on the Install button</br>
THEN I download my web application as an icon on my desktop</br>
WHEN I load my web application</br>
THEN I should have a registered service worker using workbox</br>
WHEN I register a service worker</br>
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets</br>
WHEN I deploy to Heroku</br>
THEN I should have proper build scripts for a webpack application

## Installation

To install this clone the repository and run `npm i` to install packages</br>
Then run `npm run start` in the root directory to start the application

## Preview

You can find this deployed on [Heroku](https://jatebykate.herokuapp.com/)</br>
![screenshot](/JATE.png)

## Questions

You can find the code on my [Github](https://github.com/katepatch/Text-Editor-PWA)</br>
You can email me at kate.epatch@gmail.com
