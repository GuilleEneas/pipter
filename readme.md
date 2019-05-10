# PIPTER

## Pixel Perfect Frontend Tester

If you have an AngularJS App with UI Router, accessible on http://localhost:8100, you can use this tool to take a screenshot of every definied state and compare it with saved screenshots.

Wow, thats useful for pixel perfect frontend implementations! Juhu.



### Install

0. create the folder `screenshots/current` and `screenshots/reference`
1. run `npm install`
2. install a selenium server manager `npm install selenium-standalone@latest -g`
3. install a selenium server `selenium-standalone install`


### Run

1. start the selenium server `selenium-standalone start`
2. start the project you want to test, e.g. your ionic application `ionic serve`
3. start the screenshot runner `node run.js`


### Use

1. start the node server `node index.js`
2. goto http://localhost:4040
