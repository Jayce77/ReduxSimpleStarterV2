# ReduxSimpleStarterV2
A follow up to Steven Grider's ReduxSimpleStarter
At this point there are too many breaking changes to that one so I started fresh.
It includes just what you need to get started with React and Redux and nothing more including:
* WebPack 4
* Babel 8
* React 16
* Redux 4
* git ignore so you are no longer pushing up the node modules folder
* Source Mapping for debugging
Getting Started

There are two methods for getting started with this repo.
Is this a new project?

Checkout this repo, install dependencies, then start the gulp process with the following:
```
> git clone https://github.com/Jayce77/ReduxSimpleStarterV2.git
> cd ReduxSimpleStarter
> npm install
> npm start
```

Are you up dating an existing project?

Click [here](https://github.com/Jayce77/ReduxSimpleStarterV2/archive/master.zip) then download the .zip file. 
1. Extract the contents of the zip file into a temporary forder
2. Copy the dist folder into your project directory
3. Copy your index.html into the dist folder
4. Copy over .babelrc .gitignore webpackconfig.js and replace the file in the project directory
5. Delete your node_modules folder and package-lock.json
6. From your project directory's project.json, copy any dependencies into the new project.json
7. Copy the new project.json into your project directory
8. Open your terminal, change to the project directory:
```
> npm install
> npm start
```
