# e2e-test-suite

> Extended end-to-end testing suite for running Cypress tests in multiple deployment environments and outputting an html test report.

**note:**
All deployment environments config file are located in directory cypress/configs
Respective test data files are located in directory cypress/testData

## Use

1. Install module deepmerge to combine default config file cypress.json with desired config file(dev.json/qa.json/uat.json:
$ npm install --save deepmerge

2. Take a look at Makefile for desired actions to run
Example command - test-dev for running cypress tests in dev environment with respective test data file.

3. npm i --D mocha mochawesome mochawesome-merge mochawesome-report-generator

3. npm run generate:html:report
open the following webpage to view the report:
e2e_test_suite_v2/TestReport/cypress-tests-report.html
