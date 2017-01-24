#The Text editor

You may have heard that there is a text editor war out there, and you want the best of the best text editor for writing javascripts better than anyone else.

Or you may want to be a hardcore dev master ninja and write javascript code on paper then rewrite it on notepad.

Truth is, you NEED a good text editor meant for coding. It will become a second nature tool to you as you build more and more with it.  

There are a lot of options out there but I personally love atom.

Atom is highly customizeable, configurable, has an active community, and really has everything you could want in a text editor. It is made by the team over at github. It is what I recommend, and can help you with it in this class. If you choose another, you are at your own risk in keeping up if you don't understand something! Don't let that deter you if you'd think you'd prefer another editor.

[Download atom and follow the instructions to install it here!!!!](https://atom.io/ "Get Atom text editor")

Sublime text is probably the biggest text editor on the market for javascript. I have never used it, but it is free, although they do ask that you pay at some point, you can use the free license forever. There are a lot of tools for writing code very quickly that may have advantages over atom in the long run, and its been around for longer so there are more tutorials for becoming a power user.

vim if you wan't to be really hardcore this is a bash(terminal/command line) based text editor. It is very popular and has a big community of great developers making packages for it.

You probably should not go with any paid text editor or IDE. You just won't need it for a long time. The ones recommended above are powerful enough to do everything you need even at a very advanced, professional, level.

There are a lot more options out there, these are the ones I am familiar with, feel free to do your own research.

---
#Suggested packages

###Coloring code for React and es6

After downloading Atom, since we will be working with react and es6 very soon, we should get a package that properly color codes our react syntax. This will make reading the code MUCH easier.

find your atom preferences page >> navigate to "Install +" >> search for babel. Then download the language-babel package that has 700000+ installs.


[next >>](./03: Node.js time!!!.md)


##A plug for Nuclide!
**A member of the event, Mitch Rees-Jones, shared this on our facebook page, I thought it was an excellent write up. I would totally encourage anyone to try nuclide**

Hey all! If you're looking for a great React/Javascript editor, I'm going to make a plug for Nuclide (https://nuclide.io), Facebook's IDE built on top of Atom.
#### Background 
Atom (https://atom.io) is an open-source editor built by GitHub that you can customize by installing packages written by developers like you. Nuclide is a package for Atom that adds IDE functionality + features to help your development workflow, including for React and Javascript. Facebook built Nuclide to help Facebook developers be productive, but over time they realized that it would be useful for the rest of the world, so they open sourced it!
#### What features does it have?
Nuclide has a diverse set of features, some of which are helpful for both general development and some for React/Javascript development. I've outlined a few features below:
0. THE BASICS: Syntax highlighting, autocomplete, etc.
1. QUICK OPEN: It's a search box that lets you find and open files from the project you're working on.
Mac: cmd+T
not Mac: ctrl+T
2. COMMAND PALETTE: It's a search box that lets you to find and invoke any Atom or Nuclide command. Useful if you can't remember a keyboard shortcut.
Mac: cmd+shift+P
not Mac: ctrl+shift+P
3. FILE TREE: Atom has its own file tree but Nuclide disables that and replaces it with a better one. It's better because it adds a clickable list of open files and files with uncommitted changes.
4. DEBUGGING: There's a built-in debugger. Info on how to use it: https://nuclide.io/docs/features/debugger/
There's also a React Native debugger! (React Native is React development for mobile apps)
Mac: cmd+shift+A
not Mac: ctrl+shift+A
5. DIAGNOSTICS: Shows errors in your code. You can set up ESLint, Flow, Typescript, and other Javascript code-checking utilities and the errors will show up in the diagnostics tab.
Mac: Not sure, try the command palette to find it
not Mac: alt+shift+D
6. CODE NAVIGATION: There's an Outline View sidebar that shows an outline of the current file - it shows a list of functions, classes, methods, variables, etc. on the right. You can click on each to move your cursor to that function/class/etc. in the file.
Mac: option+O
not Mac: alt+O
7. REMOTE DEVELOPMENT: If you have a remote server that you write your code on (a common practice in software companies, including Facebook), you can remotely edit those files in Nuclide as if they're local. There's a small bit of setup to install Nuclide on the server you're connecting to, but other than that it just works.
