# README

# CREDITS

* apickli (for api testing): https://github.com/apickli/apickli
* gulp protractor cucumber html report: https://github.com/mrooding/gulp-protractor-cucumber-html-report

## How do I run tests?

* Run `gulp jenkins` for regression tests

## How do I run API tests?

* Run 'node_modules/cucumber/bin/cucumber.js --require e2e/steps/api.js e2e/features/api/'

## Browserstack

* Download BrowserStackLocal (https://www.browserstack.com/browserstack-local/BrowserStackLocal-darwin-x64.zip)
* ./BrowserStackLocal [browserstack key]
* Run `gulp e2e:bs` for regression tests


## Step definitions

#UI

I am on the logout page
I am on the "page name" page
I click the "button identifier" button
I fill in "field identifier" with "([^"]*)"
I select "dropdown option value" from "dropdown identifier" dropdown
I select tomorrows date from date dropdown
I should see "expected value" in the "area identifier" area
I should not see "expected value" in the "area identifier" area
"count of errors" fields are displayed with error message
I get count of all DOM elements
I fill the form with the following data
I should see form data
I complete all form fields on form one
I should see the "field identifier" field
I should not see the "field identifier" field
I should see value "expected value" in the "field identifier" field
I should not see value "expected value" in the "field identifier" field
"field identifier" field should be disabled
I click the "field identifier" checkbox
the correct first available time displayed

#API

I set (.*) header to (.*)
I set body to (.*)
I pipe contents of file (.*) to body
I have basic authentication credentials (.*) and (.*)
I set bearer token
I GET $resource
I POST to $resource
I PUT $resource
I DELETE $resource
response header (.*) should exist
response header (.*) should not exist
response body should be valid (xml|json)
response code should be (\d+)
response code should not be (\d+)
response header (.*) should be (.*)
response header (.*) should not be (.*)
response body should contain (.*)
response body should not contain (.*)
response body path (.*) should be (.*)
response body path (.*) should not be (.*)
I store the value of body path (.*) as access token
I store the value of response header (.*) as (.*) in scenario scope
I store the value of body path (.*) as (.*) in scenario scope
value of scenario variable (.*) should be (.*)
I store the value of response header (.*) as (.*) in global scope
I store the value of body path (.*) as (.*) in global scope