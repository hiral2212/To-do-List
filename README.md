# To-Do-List
Checkbox: To mark the completed task. Create a checkbox
Input element: To show and edit the task.
We are going to use localStore to store our tasks so that we can access them later.

-> localStorage
localStorage is a global object that is used to store data locally on a user's computer.
It is used to store data in a way that is accessible by the user's web browser.
localStorage is a key-value storage system.

To add a new task first create a javascript function with the name 'addTask'.

Within the function first, check if the task is empty or not. If it is empty then return and alert the user.

Then check if the task is already present in the list or not. If it is present then return again and alert the user.

If the task is not present in the list then add the task to the list and store it in localStorage.

If the task is not empty then create a new li element and set its innerHTML with the HTML code for list element and put the task value in it using backticks.

You can add, edit, remove and mark tasks as completed. You can also save your tasks to local storage and load them when you open the app again.
