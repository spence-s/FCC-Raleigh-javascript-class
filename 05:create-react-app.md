#Installing create-react-app

(buckle your seatbelt kids, its about to get a lot more in depth)

##What is create-react-app?

create-react-app is a package, maintained by facebook, which provides us with all the starter code we need to write a react application.

1. In your shell type `npm install -g create-react-app` and wait for it all to download
2. In your shell type `create-react-app learn-react` and wait for it download

What did we just do? create-react-app has its own CLI ('command line interface'). The command create-react-app followed by a block of text signals the create-react-app cli to make a new project in a new directory with the name of your second argument.

At this point you should(hopefully) have your your new react app all downloaded.

Awesome. Lets explore. create-react-app does a lot for you to abstract away all the complexity involved in making a react app. It still may look confusing, but we will explore in just a minute many other things that make create-react-app so awesome for starting new react projects.

First, let's open up our package.json file in our newly created react app.

`atom package.json` (this only works if you are using atom text editor)

You will see that for dependencies, there are only 2, react and react-dom. There are three scripts called start, build, test, and a fourth called eject.

See, when a react app is created through create-react-app instead of listing the dependencies, they use this kind of behind the scenes code called react scripts to run your program.

##Ejecting a create-react-app
You will see in your scripts that you have an npm run eject script avaialable to you to run in the terminal. 

type: `npm run eject` in your terminal 

You will see the terminal working. After it is finished, go back to your project, then inpsect your package.json.
A lot has changed! Now there are lots of dependencies listed! Holy cow. 

You may not have been aware but there is a lot going on behind the development of a react app!

Create react app is a utility that takes all that out of your hands so you can focus on javascript and not on setup! 

You may want to eject your app when you become an advanced react coder and want to customize your setup, for now, let's just forget that all this is going on behind the scenes. Unfortunately, once you eject out of your create-react-app set up, there is no way to go back. The only way to get rid of all that stuff in your project is to create a  new create-react-app. There is nothing wrong with writing your code in the ejected app, but I prefer to have my code and projects as clean and easy to read and understand as possible... Especially while I am learning. 

Let's go ahead and create a new project. 

Go to your terminal and navigate to a folder where youd like to create a new project. 

In your shell type `create-react-app hello-world` and wait for it download.

###More on create-react-app
Create react app is a very complex package that makes development very simple. However, you may be interested in learning more about what is going on behind the scenes in your react project. We will not cover that in this tutorial/blog/writeup but we can point you to some solid rouesources.

One of the best resources is the [documentation for create-react-app](https://github.com/facebookincubator/create-react-app). 

Another resource, which we will begin using heavily, and that I highly reccomend as a supplemental guide for learning react is the free e-book by fullstack-react called [30 Days of React](https://www.fullstackreact.com/30-days-of-react/)

Get it here: [30 Days of React](https://www.fullstackreact.com/30-days-of-react/)

30 Days of React will help you cement and explain the knowledge we cover here. If this is your first time learning React, you will need a lot more work than just this class to remember all the concepts and what not. 
I will also be referencing some examples and well worded explanatiions from there as well throughout this class/course/blogpost/ whatever the hell this is. 

Create-react-app is talked about it chapter 12 of the e-book, but the explanations for the moving parts of React that come before that are very very good. 

next well start diving into some react code itself! I reccomend reading the first 4 chapters of the e-book before moving forward. 


[next >>](./06: Comppnents, Classes, and Elements.md)