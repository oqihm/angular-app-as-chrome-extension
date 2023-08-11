# Steps

Create a new Angular App
Install angular-types/chrome (npm i -D @angular-types/chrome)
Add manifest.json to src
Add devtools.html, devtools.js to src
## devtools.html will be the starting to point to load devtools.js
## devtools.js will create the chrome panel; set panel's initial page to index.html since it's our index file in angulage.json(can be changed directly to devtools.html)
Add manifest.json, devtools.html, devtools.js to angular.json => assets
Build App
Add dist folder as chrome extension

![Alt text](<docs/Screenshot 2023-08-11 at 1.10.39 PM.png>)
![Alt text](<docs/Screenshot 2023-08-11 at 1.14.10 PM.png>)
