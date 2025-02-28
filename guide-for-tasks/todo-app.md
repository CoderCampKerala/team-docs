**Project: To-do App**

Project Description

Create a To-do application using HTML, CSS, and JavaScript. The To-do app should allow users to add, view, and manage a list of tasks.
Requirements
1. Add New Tasks
   * An input field and button should let users add a new task.
   * The new task appears in a task list on the page.
2. Mark Tasks as Completed
   * Each task should have a way to indicate if it’s completed (e.g., a checkbox or a strikethrough).
3. Delete Tasks
   * Users should be able to remove a task from the list if they no longer need it.
4. Application Structure
   * Use HTML for the structure.
   * Use CSS to make it visually appealing and user-friendly.
   * Use JavaScript for all the interactive features (adding, deleting, marking tasks).
5. (Optional Bonus): Persist Data
   * Store tasks in local storage (or another storage mechanism) so that the tasks remain even after the page is refreshed.
Suggested Steps to Complete the Project
1. Set Up Your HTML & CSS
   * Design a simple layout for your to-do list: a header, an input field + button, and a main area where tasks will appear.
   * Style it with CSS to make it look neat (optional for a minimal version, but encouraged for practice).
2. Plan Your JavaScript
   * Identify which elements you need to select in the DOM (e.g., the button, the input field, the task list container).
   * Decide how you will handle adding tasks, marking tasks, and deleting tasks.
3. Implement Adding Tasks
   * Write a function that captures the input value and creates a new list item (or similar structure).
   * Append the new item to the task list.
4. Implement Marking Tasks as Completed
   * Add an event listener for clicks on the task or checkbox.
   * Toggle a CSS class to visually represent “completed” status (e.g., text-decoration: line-through;).
5. Implement Deletion of Tasks
   * Add a delete button or icon next to each task.
   * On click, remove the corresponding task element from the DOM.
6. (Optional) Implement Local Storage
   * Use localStorage to save tasks.
   * On page load, retrieve and display the saved tasks.
