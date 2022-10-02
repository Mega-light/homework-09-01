# Homework 09-01

## Instructions

In the test lifecycle, use -Dbrowser to select the browser option. You can use drivers like:
* Chrome
* Firefox
* Edge
* Opera
* Chromium
* Safari
* IExplorer

## Exercise
1. Parameterize your project, so you can send the browser option from the command line. E.g: mvn test –Dbrowser=firefox
2. Create a test suite for UI tests and another one for API Tests
3. Push your project to a GitHub repository
4. Create a new Jenkins Job (For UI tests) and configure your maven project (remember you have a parametrized project)
5. Schedule a build using below criteria: Every 2 hours from Monday to Friday
6. Create a new Jenkins Job (For API tests) and configure your maven project
7. Schedule a build using below criteria: At 6:30pm on Monday, Wednesday and Friday
