# ACA Cypress Test

## Setup
1. Fork this repository
1. Install [NodeJS](https://nodejs.org/en/download/current/)
1. Run `npm install` in the root folder
1. Run `npm install --global gulp-cli` to Install [Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)
1. Run `npm install --global @angular/cli` to Install [Angular CLI](https://github.com/angular/angular-cli)
1. Run `npm install --global cypress` to Install [Cypress](https://cypress.io)

## Development

To run the dev server use the command `gulp serve`
To run cypress along with the dev server use the command `gulp test`

## Task

Test all the functionality of the time picker component on the sample angular component.

Items to test:
 - Change the start time using the clockface
 - Check that the end time updated to keep the duration
 - Change end time using the clockface
 - Check the duration has updated correctly
 - Check that changing the period qualifiers(AM/PM) updates the values approriately
 - Check changing to manual input(keyboard icon)
 - Check changing start time manually
 - Check changing end time manually

