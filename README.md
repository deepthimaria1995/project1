# Zendesk-Coding-Challenge - Submission

A command line interface based application that is written in javascript using the Node.js runtime. The app makes HTTP requests to the Zendesk API to retrieve account tickets displayed in either a summary table or full details format. The task had a one week deadline to create and submit the application.

## Prerequisite Installations

- [NodeJS](https://nodejs.org/en/) v10.16.0 or greater
- NPM v6.9.0 or greater (At the time of making this documentation, NPM comes with the Node.js installation)

## How to run

Download the repository to your local machine with the following code.
$ git clone https://github.com/deepthimaria1995/Zendesk-Coding-Challenge

Navigate to the Zendesk-Coding-Challenge repository directory in your Terminal.ins
Install all npm modules with the following code.
$ npm install

Start server from console with command. That will give you a link to access the webpage.
$ serve

Your index.html page will be available on URL which comes as the outcome of the command in the console. Open the link in browser.

### Main Component Description

- ```app.js``` : Program entry point, prime implementation and controls the flow of the program.
- ```Subscription.js``` : Creates the subscription UI layout.
- ```UtilityHelper.js``` : Functions which deal with the error,show/hide of DOM elements.
- ```PlanDetails.js``` : Containes the Plan details of the subscription of the product.


