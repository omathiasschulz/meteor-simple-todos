# meteor-simple-todos

Run the application

`cd meteor-simple-todos && meteor`

## Inserting tasks from the server-side database console

Connect to the database

`meteor mongo`

Creating a new task

`b.tasks.insert({ text: "Hello world!", createdAt: new Date() });`
