# carly-test-project

> A Vue.js project
For this project you will bootstrap a new project skeleton and add some logic to make a simple custom webapp. You will configure deployment and publish the app on Github Pages.

# Build Setup
- Can be done through the VS Code terminal
- Install Vue-CLI by running the command `npm install -g vue-cli`

## Bootstrap the Application
Once Vue-CLI is properly installed, we can bootstrap our project skeleton. This will create all the needed files to start writing our application. Create a new app using the webpack by using the command `vue init webpack test-project`
- There will be a few questions to answer.
- Once the project skeleton is available, `cd` into the directory where your project was created.

## Install dependencies
`npm install`

## Once the installation is complete, we can test the project by running:
`npm run dev`

## Get familiar with the different Vue.Js components by:
- Modifying the "Hello" components in `src/components/Hello.vue`.
- Changing the styles in the `src/App.vue` template.
- Modify the logic by changing the wording of the `msg:` variable.
- Add an event handler by creating a button that calculates two sums when it is clicked.

# Practice debugging
- Make sure that you have the Vue-Devtools installed on your browser.
- Open the Vue-Devtools panel, to watch the value change when the Calculate button is clicked.
- To learn what happens during a sytax error you should create one. Do this by adding a semicolon to the data oject (after the word 'null').
    - You should see warning messages popped up in several different places.

# Deploying the App

## Create a Github repository
In Github create a new repository. You can name it anything you want. Make sure to add a description. 
- It can be either public or private.
- No need to make a `README`file.

In VS Code Terminal
- Run the `git init` command to make a Git repository in the directory
- Add all the files you have been working on by using the command `git add -A`.
- Run `git status` to see the files you need to commit.
- Make your first commit to your master branch by running the `git commit - m 'first commit'`.
- Add the remote url server by copying the information from the Code section of your Github repository.
- Connect the master branch to the origin server by using the `git push -u origin master` command.
You should now be able to see your files on Github

## Configure the Webpack
- In the `config/index.js` file change "dist" to "docs".
- While in the `config/index.js` file set the `assetsPublicPath` to `''`.
- Build for production with minification by using the command `npm run build`. 

## Configure Github Pages
- In the setting tab change the "Source" to master branch/docs folder. Then click save. 
- Copy the link and pasted it paste it in the main heading of your repository. 

## build for production and view the bundle analyzer report
npm run build --report

For a detailed explanation on how things work, check out the 
[guide](http://vuejs-templates.github.io/webpack/) 
and [docs for vue-loader](http://vuejs.github.io/vue-loader).
