#What this is:
Sandbox environment to build a web component.
All you have to do is modify the MyComponent for what you need.

##Prereqs
Make sure you have node, npm, gulp installed on your computer

    [node+npm](https://nodejs.org/en/)


install gulp:

    npm install -g gulp

##To use:

1. Start web server - In root, run:

    ````node server.js````

2. Go to: http://localhost:3000/

3. Edit your component at public/MyComponent/

##Using Gulp:
Gulp allows you to compile the react code to javascript code. Gulp also compiles sass

1. Compile JS

    ````gulp build ````

2. Compile sass

    ````gulp sass ````

3. Watch changes.

    ````gulp watch ````

