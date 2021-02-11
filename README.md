# SASS-Beginner-To-Advanced
This will help you get started with SASS very easily
For the sake of learning and keeping this repo size to a limit node modules packages have been ignored.
# GET STARTED
1. Install npm easily by following instructions on official website
2. Open a command line in the folder where you have cloned it. Run this command
```
npm install
```

# How to compile your scss file and make your html webpage work?
1. Open your terminal in this folder
2. Run this command
```
npm run compile:sass
```
3. Close the terminal and it will stop compiling scss code..

# Make your own local scss project(Skip, Come back Later)
1. After creating a folder structure. Come back to the parent folder and open a terminal
2. Initialise npm package.json. By the following code.
```
npm init
```
3. Fill out the package info. Leave defaults for the things you don't understand.  
4. Install SCSS compiler or any other packages you want to install like jquery which will create the node modules folder.
```
npm install node-sass --save-dev
npm install jquery --save
```
The --save-dev are called dev dependency which are optional while jquery are called dependency in package json format.
Don't install jquery it has been just given for sake of info. If you are using it go ahead.
5. Modify the pacakge.json scripts line as instructed below...
6. Follow the above steps to compile. It will be same.

# Inner workings of package.json(Skip, Come back later)
You should skip this for now and come back later to understand how you can modify your package.json to help you further down the line.
1. Scripts tag is where the real things happen. You neeed to put there what packages you want to use and in correct syntax as directed by their owner. For example-:
```
"compile:sass": "node-sass sass/main.scss css/style.css"
```
Here compile:sass is just a name.
Okay so the first part is node-sass which is the package name that you are gonna use.  
sass/main.scss is the input file while css/style.css is where the output of scss file will go in pure compiled css.  
-w is the watch modifier so that terminal is switched to watch mode and you don't have to run the next command I am gonna tell you. Everytime you make modiication to scss your terminal will compile it automatically for you and output it.  
