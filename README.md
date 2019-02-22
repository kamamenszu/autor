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
* cucumber - version 5.0.3
* typescript - version 3.0.1
* protractor - version 5.4.0
* chai - version 4.1.2
* ts-node - version 7.0.1

## Status
Project is: _in progress_.

## Contact
Created by @testarmy - feel free to contact us!
