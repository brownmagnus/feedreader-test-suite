# Feedreader application with a test suite
===================================================

## Description
This project is a web-based application that reads RSS feeds. The application included a testing suite to ensure all the code run correctly using [Jasmine](http://jasmine.github.io/).


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Testing is an important skill to have, So that even if I work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, I will be able to add value.


## What I learnt

I learnt how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.


## How writing tests helps my career

* Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.
* Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.


# How to run the application

1. Open the `index.html` of the application
2.  Click on all the test outline checking that all required tests for the project pass
3. Pass means the spec will be in green and no red
4. The test are as follows:
  i. `RSS Feeds` -> `are defined`, `URL defined` & `name defined`
  ii. `The menu` -> `is hidden menu` & `toggles menu visibility`
  iii. `Initial Entries` -> `completes work`
  iv. `New Feed Selection` -> `loaded feeds content do change`
5. The Feeds loads above the test area.
