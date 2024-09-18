# NodeJs-TypeScript-Template

You can use this template for a quick setup, if you want to create a project
using node.js and typescript. This is not the most useful repo out there, but
you can save a few minutes. If you don't know how to use the template, follow
the step by step guide.

NOTE: It could be that the dependencies are not up to date. You can update them
yourself or use `npx npm-check-updates -u` to update all dependencies.

# Step by step guide

1. Don't clone this repo, just open [package.json](https://github.com/QYUbItx/Node.js-TypeScript-Template/blob/main/package.json) press Ctrl+A and Ctrl+C on windows
or Command+A and Command+C on mac os to copy the whole content of the file.
1. Create a package.json file in the root directory of your project and insert
the content via Ctrl+V / Command+V. Then save the file.
1. Open the terminal in your root directory (most IDEs have a integrated
terminal) and run `npm i` with npm or `yarn` with yarn to install the dependencies
and create the tsconfig.json file.
1. Search in the tsconfig.json file for the option "outDir" and set it from ./
to ./dist.
1. Last but not least you may want to change some values in the package.json
file to fit your project, such as "name", "version", "author", "description",
"license" and "keywords".
1. You ready to start coding!

# Contributing

If you notice a mistake or want to add something valuable, feel free to create
an issue or a pull request. 