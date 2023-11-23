Not having tests in your app is a pain because chances are every time you make slight adjustments to your app you have to manually check every single part of your app to see if anything broke. Writing tests, however, also feels for the most part a chore. But we definitely need them.

Why the fuss around automated testing? With automated tests you don’t have to test all the workings of the app every time you change something in your enormous and still growing app. This means that when you are adding or modifying parts of your app, you will have a lot more confidence in the reliability of your code. Which is really reassuring.

In this article, we’ll look into testing node apps. We’ll use Mocha, Chai, and SinonJS, and delve into using spies, stubs, and mocks. You’ll need to be familiar with Node.js and JavaScript

Mocha
Mocha is a test runner. This just means that it is a tool that runs and executes our tests. The tests themselves aren’t written in Mocha. Other test runners include Jasmine, Jest.

