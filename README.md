# JavaScript App Skeleton 2016

This is a skeleton for creating JavaScript application in 2016. It will most probably be relevant in the years to come. See the blog post [here](https://medium.com/@radoslav.popov/how-i-started-a-javascript-project-in-2016-with-bare-minimum-of-tools-78eae9b87238).

## What's the idea

Write all your code (JavaScript, SASS & HTML) in src/, then build in dist/.

## How to build the project
> - Install node.js
> - Run ```npm install``` to download dependencies
> - Run ```npm run start``` - Triggers rollup, copyfiles, node-sass, nodemon & browser-sync. In addition, browser-sync starts a web server, so the application is available on http://localhost:3001/.

If your build is successful, the dist/ directory should look like the one in the [build branch](https://github.com/Neverlastinger/JavaScriptApp2016/tree/build/dist):
> - index.html the same as the one in src/
> - img directory created and img.svg the same as the one in src/img/
> - _polyfills directory created and promise.min.js the same as the one in src/_polyfills
> - bundle.js & bundle.js.min built from src/js/main.js & src/js/App.js
> - styles.css built from src/sass/main.scss
