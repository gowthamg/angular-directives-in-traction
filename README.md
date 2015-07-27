Angular Directives in Traction
=========

AngularJS is a super-heroic JavaScript Framework that makes writing single page applications a breeze. It allows you to expand HTML vocabulary by creating custom tags with a help of directive definition object. AngularJS bundled with a set of directives like ngRepeat, ngModel, ngView which make it really easy to build an application but many a times the existing directives fell short considering the need and complexity you are dealing with. And you face the problem head-on when it comes to build directives from ground ups. This book teaches you to extend AngularJS by writing custom directives and motivates to understand the purpose of testing by facilitating Test Driven Development through out the book.

**Angular Directives** in Traction helps you understand how built-in directives work and teaches you to build custom directives on your own. Ultimately, Angular Directives will be the magic revealed for you.

Installation
--------------
Please download the source code and put it in the root directory of any web server installed on your system. **Web Server is a must for protractor tests to run.**

NodeJS and NPM are prerequisite.
```sh
cd Angular Directives in Traction/
bower install
npm install
npm install -g karma-cli
node_modules/protractor/bin/webdriver-manager update
```

There are chapter wise folders you can go through to check out examples.

Run tests
-------------
First of all, **update baseUrl in e2e.conf.js** accordingly. Then run:
```sh
npm run test-unit

npm run test-e2e
```

Using the Companion Suite
-------------------------
*Chapter 1: ch01/*
 * notification-panel-javascript.html
 * notification-panel-angular.html
 * twoway-databinding.html
 * di.html
 * angular-template.html
 * accordion-tb.html
 * accordion-ab.html
 * noop.html

Table of Contents
-----------

1. AngularJS Directives: A forerunner of Web Components
2. AngularJS Fundamentals: A Crash Course
3. Testing the Beast: Unit testing and E2E testing
4. Building your first HTML element using the API
5. Understanding Scope in Directives for better context
6. Crafting directives to handle Complex Scenarios
7. Bringing directives to Life
8. Making Directives Robust: The Guidelines

License
----

MIT