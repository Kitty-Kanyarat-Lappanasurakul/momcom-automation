# MOM.COM Automation

Install npm on your computer (ref: [click here](https://blog.teamtreehouse.com/install-node-js-npm-windows))

- To check if you have Node.js installed, run this command in your terminal:
  `node -v`

- To confirm that you have npm installed you can run this command in your
  terminal: `npm -v`

or

Install yarn on your computer (ref: [click here](https://yarnpkg.com/lang/en/docs/install/#windows-stable))

- Test that Yarn is installed by running: `yarn --version`

## How to clone the project

1. Install git on your computer (ref: [click here](https://git-scm.com/downloads))
2. Open Git Bash
3. Go to your directory on Git Bash e.g. C:\Users\User\Projects
4. Execute the command:
   `git clone https://github.com/RY-Cafemedia/momcom-automation.git`
5. Go to your folder on Git Bash e.g. C:\Users\User\Projects\momcom-automation
6. Execute the command: `npm install` or `yarn install`

## How to run the project

Go to your project directory first and execute the command below.

`npm run cypress:open`

or

`yarn run cypress open`

## How to run the project with html reports

Default browser is chrome

`node cypress_runner`

You can choose browser between chrome and electron

`node cypress_runner -b chrome`

`node cypress_runner -b electron`

## Remark for html reports

Please use the version below in `package.json`

```
"ls": "^0.2.1",
"mocha": "5.2.0",
"mochawesome": "^4.0.1",
"mochawesome-merge": "^2.0.1",
"rimraf": "^2.6.3",
"yargs": "^13.3.0"
```

## Suggestions

1. Code editor: Visual Studio Code
2. Install Prettier - Code formatter on Visual Studio Code

## How to install Prettier - Code formatter

1. Go to View > Extenstions on Visual Studio Code
2. Search "Prettier"
3. Install Prettier
4. Click on Install
5. Go to File > Preferences > Settings
6. Click on "Text Editor"
7. Click on "Formatting"
8. Select "Format On Save"
