#Installing create-react-app

(buckle your seatbelt kids, its about to get a lot more in depth)

##What is create-react-app?

create-react-app is a package, maintained by facebook, which provides us with all the starter code we need to write a react application.

You might be thinking to yourself, "Gee why do I need a starter package to write some React code? I can use jquery with just some simple script tags?"

Before we answer that question, lets actually take a look at some react code. I think it will help a lot if we have a react project that we can look at, and then explain what is going on with all that code!

1. In your shell type `npm install -g create-react-app` and wait for it all to download
2. In your shell type `create-react-app learn-react` and wait for it download

What did we just do? create-react-app has its own CLI ('command line interface'). The command create-react-app followed by a block of text signals the create-react-app cli to make a new project in a new directory with the name of your second argument.

At this point you should(hopefully) have your your new react app all downloaded.

Awesome. Lets explore. create-react-app does a lot for you to abstract away all the complexity involved in making a react app. It still may look confusing, but we will explore in just a minute many other things that make create-react-app so awesome for starting new react projects.

First, let's open up our package.json file in our newly created react app.

`atom package.json` (this only works if you are using atom text editor)

You will see that for dependencies, there are only 2, react and react-dom. There are three scripts called start, build, test, and a fourth called eject.

See, when a react app is created through create-react-app instead of listing the dependencies, they use this kind of behind the scenes code called react scripts to run your program.
