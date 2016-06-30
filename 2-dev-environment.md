---
layout: default
title: Dev environment
unitstandard: 115388-SO2-AC1, 115388-SO2-AC2, 115388-SO2-AC3
---

# Set up your dev environment

Make sure your `README` lists all the software they'll need to install on their local system. They'll probably need:

* NodeJS
* npm
* MySQL

Anything else?

## Install the dependencies

How does someone install the dependencies they need for your project? If they run `npm install`, how does NodeJS know what things to install?

You've run `npm install --save <modulename>` a few times now when coding your app. What does it do? What if we switched `--save` for `--save-dev`? If you're not sure, have a look at [Specifying Packages](https://docs.npmjs.com/getting-started/using-a-package.json#specifying-packages) in the npm docs.

How about the database? What scripts does someone have to run to set up their local database?
