steps to host app on github:

git init

1. create new repo on github
   2.copy https key
2. In project root folder --> git remote add origin 'copied https key'
3. in proj root folder --> npm i gh-pages
   5.add below lines in package.json
   "homepage": "https://NikitaBhutada2012.github.io/monster-rolodex",

"predeploy": "npm run build",
"deploy": "gh-pages -d build" 4. in command line run -->
