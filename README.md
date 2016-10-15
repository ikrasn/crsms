CRSMS

Course Managment System

## Setup project
*Note:* [Node.js](https://nodejs.org/en/) and [Ruby](http://rubyinstaller.org/downloads/) must be installed on you OS system

1. Install global components
In any folder
`npm install -g grunt-cli`
`npm install -g bower`
`npm install -g json-server`
`gem install sass`

2. Install project components:
In project root folder
`npm install`
`bower install`
`json-server --watch db.json` or `node server/index.js` - to run local api service on port 3000 (http://localhost:3000)
`grunt build:dev` - to copy vendors libraries to dev environment and to build project for development
`grunt server:dev` - to run local server on port 8034 (http://localhost:8834) with livereload for development
`grunt build:prod` - to build production version of project
`grunt server:prod` - to run local server on port 8834 (http://localhost:8834) with livereload for development
