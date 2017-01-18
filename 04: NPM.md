#NPM

Ok, Now that we have node installed, we need to learn about a new concept and tool that will be in our arsenal from this day forward.

This tool is called NPM.

NPM stands for "Node Package Manager"

Basically a "package manager" takes care of downloading and installing chunks of code and programs for us in the node environment. Anyone can create a nodejs package and upload it to the public npm package repository and download others code as they want. This way everyone can share in an easy to use open source community.

You don't have to install NPM it came with your node installation.

NPM is ran through a CLI or "Command line interface"... rememeber that word kids, you will see it a lot. A CLI is a set of commands that will run a particular chunk of code in a particular way for you. Just like the browser is a visual interface, the CLI is an interface through a command line that you read and write with.

type npm --v in your command line. Get something back like 4.0.3?

Great! You verified your npm installation.

npm allows you to download packages from the internet. Once you are in a folder on your command line. You should be able to see what folder you are in. I want you to do the following.

type
1. mkdir apps
2. cd apps
3. npm init

See what happens, and look in your folder you now have a package.json file in there

what is a package.json?

It is the folder that manages your dependancy packages. See when you write code the code you write will depend on code someone else writes. Don't worry, their code will stay online and be maintained.

The package.json will let you see what versions of what local code you are using in your local project.

Some packages are meant to be installed globally.

We manage global packages with npm too.

What do I mean by globally? Basically, once you install a package globally it just gets installed to a folder on your computer that the command line has access to at all times.

Let me do a demonstration here.

tick tock

There is so much more to npm that you should learn.

Luckily they have such great documentation, we won't need to go over it too extensively here. Just go to https://docs.npmjs.com/getting-started/what-is-npm and follow the getting started guide all the way through.

##NPM Scripts
What are npm Scripts?

Take a look in your package.json and you will see an object key called "Scripts" with a test field beside it. You can populate this scripts your self with shell commands that will run when you type npm + the command key you want to run.

For example, I may have a start script that I want to run. I would label the script "start":"node fileIWantToRun.js"

since typing node file.js simply runs your javascript file, you can now type "npm start" and your selected file will run all the time.

Many projects have much more complex scripts which we will soon explore together.
