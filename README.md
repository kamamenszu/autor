# Cucumber automation tests for Wildmoka app.

## Installation
Make sure you have installed latest Node JS and Chrome browser. Once you clone repository, execute the following command to download all required dependencies

`npm install`

## Run Scripts
First step is to fire up the selenium server which could be done in many ways, webdriver-manager proves very handy for this.The below command should download the chrome & gecko driver binaries locally for you!

`npm run webdriver-update`

Then:
`
npm run webdriver-start`

## Executing tests
In order to start all tests scenarios, open terminal in main folder and use following command:

`npm test`

To start only one test case, specify a scenario by using tag @scenario and open terminal in main folder and use following command:

`npm run scenario`

**NOTE:** Please look at animation to see how run particular scenario:

## Technologies
* cucumber - version 5.1.0
* typescript - version 2.7.2
* protractor - version 5.4.2
* chai - version 4.2.0

## Status
Project is: _in progress_.

## Contact
Created by @testarmy - feel free to contact us!
