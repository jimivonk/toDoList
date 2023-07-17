TODO LIST

Description:

Build a simple web-based application where users can manage their to-do tasks. They should be able to add tasks, mark them as completed, and delete them. This will help you practice DOM manipulation, event handling, and managing application state, which are all crucial skills in JavaScript.

Core Features:

    Task Input: Include an input field where users can type in their tasks and a button to add the task to the list. When the button is clicked, the input field should be cleared.

    Task Display: Display tasks in a list format. Each task should have a checkbox to mark it as completed and a button to delete the task. Uncompleted tasks could be shown in normal text, while completed tasks could be shown as struck-through or greyed out.

    Task Completion: When a user clicks on a task's checkbox, it should visually indicate that the task has been completed. This could be as simple as applying a CSS class that crosses out the text.

    Task Deletion: Each task should have a delete button next to it. When clicked, the task should be removed from the list.

Implementation Steps:

    HTML & CSS Setup: Start by setting up your HTML structure. This should include an input field for adding tasks, a button for submitting tasks, and a placeholder area where the tasks will be displayed. Style your application with CSS to make it visually appealing.

    Adding Tasks: Capture the 'click' event on the add task button. When clicked, grab the value from the input field and use this to create a new task element in the list. The task element should include the task text, a checkbox, and a delete button.

    Marking Tasks as Completed: Attach a 'click' event listener to each task's checkbox. When this is clicked, toggle a CSS class on the task element to visually indicate that it's completed.

    Deleting Tasks: Attach a 'click' event listener to each task's delete button. When clicked, remove the task element from the list.

    Persisting Tasks: (Optional advanced feature) You may wish to add functionality to save the user's tasks in the browser's local storage, so that their list persists even if the page is refreshed. This would involve saving the tasks to local storage whenever a task is added, completed, or deleted, and loading the tasks from local storage when the page is loaded.

//HTML
TASK INPUT
    - Add task instructions:
    - input box (necessary min char3 max 20?)
    - task duration: (optional)
    - time dropdown hours
    - time dropdown minutes
    - enter button
TASK LIST
    -container within a container
    -Number:
    -"Task description"
    -time to complete, default = NP
    -edit BUTTON
    -delete BUTTON
    -Toggle up/down BUTTON? (reprioritize)

//CSS
    -Reset
    -

//PROGRAMING LOGIC

TASK INPUT

TASK DISPLAY
within a box/ window
numbered
alternate colours, to make it easier to read

