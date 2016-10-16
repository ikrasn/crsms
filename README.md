#Course Managment System or CrsMS

## Setup project
*Note:* Please check if all needed components Node.js, Ruby and some others already installed.
More in [Enviroment setting on Windows OS] (./docs/enviroment-settings.md)


In project root folder

    `npm install` -install node modules
> *NOTE:* in case of errors `npm cache clean` and `npm update -g` fix problems. More in [Enviroment setting on Windows OS] (./docs/enviroment-settings.md)

    `bower install` - install bower modules


    `grunt build:dev` - to copy vendors libraries to dev environment and to build project for development
    `grunt server:dev` - to run local server on port 8034 (http://localhost:8834) with livereload for development


    `grunt build:prod` - to build production version of project
    `grunt server:prod` - to run local server on port 8834 (http://localhost:8834) with livereload for development

    `~path_to_mongo_db/mongod.exe --dbpath ~path_to_project_root\database\`
>*NOTE:* create directory in project root database before

    `cd server` - go to server directory
    create server directory and log.log file in
    `node server` - run BE server

    open `localhost:8888/api/setup` - to setup mock data

    open demo course `http://localhost:8034/#courses/5803d5ebb7b622c010f170e1`
