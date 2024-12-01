# Wise Words

### Project Introduction
This project was inspired by my interest in ancient history and dead languages. The app generates a random ancient language quote that can then be "translated" into English. The frontend app fetches quotes from a simple backend API that I wrote using Node.js, Express, and MongoDB. 

This repo is concerned with the frontend. To see the backend, click [here](https://github.com/markjager13/wise-words-api).

### How I worked on this project
* I first implemented the frontend design in HTML & CSS and ensured that it was mobile responsive.
* I then used JavaScript fetch API to asynchronously fetch quotes from the backend. 
* Lastly, I wrote a JavaScript function to trigger a CSS animation for the "translation" effect. 

### How to navigate this project
* JavaScript async fetch request: [Example Code](https://github.com/markjager13/wise-words-frontend/blob/9424c83b616b545acdba28b8363f3be24b59d308/script.js#L70)
* Toggling CSS classes to adjust font-size for longer quotes: [Example Code](https://github.com/markjager13/wise-words-frontend/blob/9424c83b616b545acdba28b8363f3be24b59d308/script.js#L34)
* Toggling CSS classes to hide/reveal English language translation: [Example Code](https://github.com/markjager13/wise-words-frontend/blob/9424c83b616b545acdba28b8363f3be24b59d308/script.js#L122)

### Why I built the project his way
* I chose to use plain HTML, CSS, and JavaScript so that I can review fundamental JavaScript concepts, such as DOM manipulations. 
* In building a quotes app, I wanted to review my understanding of making fetch requests and working with REST APIs.
* I have an interest in dead languages, so I wanted the quotes to first be rendered in their original language. 

### If I had more time I would change the following
* My translation effect is a simple fade-out fade-fade in transition using CSS. However, there could be a cooler way to animate this. One neat example is this text morph animation seen from this [codepen](https://codepen.io/Valgo/pen/PowZaNY).
* It might be nice to add a search bar so that the user could search for particular author.
