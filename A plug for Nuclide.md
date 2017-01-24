##A plug for Nuclide!

*A member of the event, Mitch Rees-Jones, shared this on our facebook page, I thought it was an excellent write up. I would totally encourage anyone to try nuclide*

Hey all! If you're looking for a great React/Javascript editor, I'm going to make a plug for Nuclide (https://nuclide.io), Facebook's IDE built on top of Atom.

#### Background 
Atom (https://atom.io) is an open-source editor built by GitHub that you can customize by installing packages written by developers like you. Nuclide is a package for Atom that adds IDE functionality + features to help your development workflow, including for React and Javascript. Facebook built Nuclide to help Facebook developers be productive, but over time they realized that it would be useful for the rest of the world, so they open sourced it!

#### What features does it have?
Nuclide has a diverse set of features, some of which are helpful for both general development and some for React/Javascript development. I've outlined a few features below:

0. THE BASICS: Syntax highlighting, autocomplete, etc.

1. QUICK OPEN: It's a search box that lets you find and open files from the project you're working on.
...Mac: cmd+T
...not Mac: ctrl+T

2. COMMAND PALETTE: It's a search box that lets you to find and invoke any Atom or Nuclide command. Useful if you can't remember a keyboard shortcut.
...Mac: cmd+shift+P
...not Mac: ctrl+shift+P

3. FILE TREE: Atom has its own file tree but Nuclide disables that and replaces it with a better one. It's better because it adds a clickable list of open files and files with uncommitted changes.

4. DEBUGGING: There's a built-in debugger. Info on how to use it: https://nuclide.io/docs/features/debugger/
...There's also a React Native debugger! (React Native is React development for mobile apps)
...Mac: cmd+shift+A
...not Mac: ctrl+shift+A

5. DIAGNOSTICS: Shows errors in your code. You can set up ESLint, Flow, Typescript, and other Javascript code-checking utilities and the errors will show up in the diagnostics tab.
...Mac: Not sure, try the command palette to find it
...not Mac: alt+shift+D

6. CODE NAVIGATION: There's an Outline View sidebar that shows an outline of the current file - it shows a list of functions, classes, methods, variables, etc. on the right. You can click on each to move your cursor to that function/class/etc. in the file.
...Mac: option+O
...not Mac: alt+O

7. REMOTE DEVELOPMENT: If you have a remote server that you write your code on (a common practice in software companies, including Facebook), you can remotely edit those files in Nuclide as if they're local. There's a small bit of setup to install Nuclide on the server you're connecting to, but other than that it just works.
