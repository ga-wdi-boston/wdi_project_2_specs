# Project Manager Spec

Your group will build a project management tool which can be used to organize/track work on software development products. It will be similar in concept to Basecamp, Asana, Redmine, etc.

### Features

- Users can create accounts
- Users can login
- Users can create a new project
- Projects have one or more owners/collaborators
- Projects can be set as public or private so that anyone in the world may view the contents and participate, or only members authorized to the project may views its contents and make changes
- Projects have tasks
- Tasks have comments through users
- Users can create, update and delete tasks on projects
- Tasks may have a due date, sub-tasks, and a priority level
- Users may have tasks assigned to them
- Users may attach files to a task, such as an image or PDF, which are intended to aid in the completion of the task
- Users can see a list of pending tasks and completed tasks

Having a clear, quick and clean workflow/UI is essential for a project management site. Every click and keystroke matters. A huge goal here is to 'get out of the way' of the user to let them do their job more efficiently.

### Optional Features

- Users may elect to receive email alerts when needed (ie. someone leaves a comment on a task they created, or when they are assigned a task)
- Users may use OAuth via Google or Github to authenticate with the site

### Gotchas

Image upload must persist to Amazon S3/Cloudfront, and handling the upload process with JavaScript is tricky. We have included some code for Rails that can help out greatly with this. Don't just blindly use the code however, and make sure that you use `pry` to trace through it completely, and potentially even refactor it.
