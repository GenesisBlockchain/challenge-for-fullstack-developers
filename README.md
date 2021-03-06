# Coding Challenge for Fullstack Developers
This challenge is to showcase skills in both backend and frontend development.

## Requirements
- React 
- Redux 
- MongoDB 
- Express
- Node

You have 3 days upon receiving this test to complete and submit it back to us

## Instructions
The purpose of this code challenge is to build an admin dashboard with authentication protection and the ability to add new tasks.

1. Clone this repository and create your own GitHub repository.
2. Push your git repository to GitHub.
3. Initialize a new React project
5. Create the login page with the following features: 
   - Text inputs for email and password.
   - Submit button.
   - Show an error message for incorrect credentials.
   - Make the page responsive for mobile and desktop devices.
   - Redirect to the admin dashboard page (to be built in the next step) for correct credentials.
6. Build the admin dashboard page:
   - Show a list of tasks (the tasks should be fetched from a database and put into a redux store). 
   - Each task has the following data: Title, timestamp, whether it's done, and description.
   - Add the option to add multiple tasks at once.
   - Add the option to edit an existing task.
   - Add the option to remove an existing task (should be removed from the database as well).
   - Pagination on tasks
   - Add a logout button that redirects to the login page. 
   - Make the page responsive for mobile and desktop devices.
7. Create the express server with the relevant APIs for the frontend to connect to. 
   - Add routes that deal with these functionality
       - Creating multiple tasks
       - Reading
       - Updating
       - Deleting 
9. When you are done, send us the link to your GitHub repository with a clear readme file and any other details required for us to run the app

## Bonus
Bonus points for 
   - adding a search bar in the admin dashboard to search for tasks. 
   - adding images to tasks
   - having a link to the deployed web app that is functional and available for use.

