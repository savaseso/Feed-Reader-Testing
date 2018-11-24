PROJECT OVERVIEW

This is a project from Udacity's Nanodegree program Front-End Web Developer. The goal of this project is execute a series of testing for an web-based application that reads RSS feeds using Jasmine testing framework.

*How to run the application:

Clone the repository with $git clone https://github.com/savaseso/Feed-Reader-Testing.git
Open index.html in the browser. This will display both the page and the Jasmine test suites (scroll to the bottom of the browser).


*The following tasks were mandatory:

Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
Write a new test suite named "The menu".
Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
Write a test suite named "Initial Entries".
Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
Write a test suite named "New Feed Selection".
Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.
