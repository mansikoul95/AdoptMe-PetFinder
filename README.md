# Pet-Finder

• Developed a real-world application called Pet Finder, using tools from the React ecosystem (like Reach Router) to build a full application to browse adoptable pets.

• The application uses the latest React features like hooks, effects, context, and portals to make the code more maintainable and reusable.

### Prerequisites

Before starting the course, please have VSCode or another code editor installed.
To understand the code you would require prior knowledge of HTML, CSS, React JavaScript Framework.

## Installing

### npm

It is the package manager for Node. It also has all the packages in the front end scene. npm makes a command line tool, called npm as well. npm allows you to bring in code from the npm registry which is a bunch of open source modules that people have written so you can use them in your project. Whenever you run **npm install react**. it will install the latest version of React from the registry.

### Prettier

Prettier is a really fancy pretty printer. It takes the code you write, breaks it down in to an abstract syntax tree (AST) which is just a representation of your code. It then takes that AST, throws away all of your code style you made and prints it back out using a predefined style. While this sounds a little scary, it's actually really cool. Since you no longer have control of the style of your code, you no longer have to think about it at all. Your code is always consistent, as is the code from the rest of your team. 

In order to do that, set **prettier.requireConfig** to **true** and **editor.formatOnSave** to **true**.

### ESList

On top of Prettier which takes of all the formatting, you may want to enforce some code styles which pertain more to usage: for example you may want to force people to never use with which is valid JS but ill advised to use. ESLint comes into play here. It will lint for this problems.

First of all, run **npm install -D eslint eslint-config-prettier** to install eslint in your project development dependencies. Then you may configure its functionalities.
There are dozens of present configs for ESLint. I'm going to use a looser one, which is **eslint:recommended**.

## Running Project

1) Extract the AdoptMe-PetFinder.zip folder. 
2) Unzip the folder and open in VSCode.
3) Open Terminal and run **npm install react** > **npm init**
4) Run **npm run dev**
5) Open server link in terminal to navigate to application home page.

