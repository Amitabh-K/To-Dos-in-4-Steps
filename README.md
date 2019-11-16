# To-Dos-in-4-Steps

Prepare to do in 4 steps: Render To dos / add functionality / Complete To dos( remove) / storing to dos in local Storage.

## Render Todos (1)

In this activity you will be writing code to render an array of todo items to the list.

### Instructions

* Open the `script.js` file provided to you. You have been provided the necessary variable declarations as well as an array of todo items.

* Your goal is to create a function that will render our todos into a list in the browser.

  * Initially set the text content of the todoList to an empty string.
  
  * todoCountSpan should show the total count of todos on the page.
  
* Inside of your render function you will also need a for loop.

  * It should loop over the `todos` array creating an `li` element for each index of the array.
  
  * It should set the content of the created `li` element to the value of the current array index.
  
  * Finally the new `li` should be appended to the `ul` provided.
]

## Add ToDo's (2)

In this activity, we will be continuing to build on our Todo activity. This time, we'll be adding the `add` functionality.

### Instructions Provided 2

* Add an event listener so that when a user hits enter, the value from the todo input field is pushed to our todo array.

* Make sure that empty values are not pushed to the array.

* Once the value has been added to the array, clear the input field and re-render the todo list.

## Complete Todos (3)

In this activity, we will create a "complete" button that successfully removes a todo item from the list when clicked.

### Instructions Provided 3

* Modify your `renderTodos()` function:

  * When a new todo is created, add a `data-index` for each `li`.

  * Generate a button that says "Complete" and append it to your `li`.

* Add an event listener so that when a user clicks the Complete button, it accesses the `data-index` value and removes that todo element from the list.

## Local Storage Todo's

In this activity, we will working on storing our todos in `localStorage`. 

### Instructions Provided 4

* Inside the `init()` function:

  * Set a variable called `storedTodos` that retrieves the todos from `localStorage` and parses the JSON string to an object.

  * Check if the todos were retrieved from `localStorage` and if so, set a `todos` variable with the `storedTodos`.

  * Lastly, render the todos to the DOM.

* Inside the `storeTodos()` function:

  * Stringify and set the "todos" key in `localStorage` to the `todos` array.
