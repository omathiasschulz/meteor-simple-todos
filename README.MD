# meteor-simple-todos

Run the application

`cd meteor-simple-todos && meteor`

Based on the tutorial [meteor blaze tutorial](https://www.meteor.com/tutorials/blaze/creating-an-app)

## Inserting tasks from the server-side database console

Connect to the database

`meteor mongo`

Creating a new task

`b.tasks.insert({ text: "Hello world!", createdAt: new Date() });`

## Running the tests for this application

`TEST_WATCH=1 meteor test --driver-package meteortesting:mocha`
