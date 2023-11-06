# Todo-List-App
Simple todo list application made using HTML/CSS and JavaScript
The architecture of your Todo List app consists of several components:

1. **HTML (index.html):** This is the user interface of your application. It contains the form for adding new tasks, the display area for the list of tasks, and includes necessary Bootstrap and JavaScript library dependencies.

2. **CSS Styling:** The app includes some custom CSS styling to improve the visual design of the page. It uses Bootstrap for styling and icons.

3. **JavaScript (todo.js):** The core functionality of your Todo List app is implemented in JavaScript. Here's a breakdown of what the JavaScript code does:

   - **Data Storage:** The app stores and manages the todo items using the `todos` object. It keeps track of todo items and assigns them unique keys.

   - **Inserting Todo:** The `insertTodo` function is responsible for inserting new todo items into the list. It creates the HTML elements for each todo item and adds event listeners for removing items.

   - **Initialization:** When the page loads, the JavaScript code fetches global todo items from a JSON file and local todo items from local storage. It populates the todo list with these items. It also sets up event listeners for adding new items and periodically checks for overdue items.

4. **External Dependencies:** The app depends on external resources, such as Bootstrap for styling and icons, which are loaded via content delivery networks (CDNs).

5. **User Interaction:** Users can interact with the app by filling out the form to add new tasks. The app validates the input and stores the tasks locally. Users can also remove tasks by clicking on the "X" button next to each task.

6. **Display:** The app displays the list of tasks in a table format. Overdue tasks are highlighted.

- The architecture follows a client-side approach where the data is managed on the client's browser. 
 - Users can add, remove, and view their tasks, and the app periodically checks for overdue tasks. It uses a combination of local storage and external data sources to maintain the list of tasks.
