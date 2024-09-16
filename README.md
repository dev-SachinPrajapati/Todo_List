
# To Do List with Local Storage

- This project is a simple To Do List web application that allows users to add, edit, mark as completed, and delete tasks.
- Tasks are stored in the browser's local storage so that they persist even after the page is refreshed.

## Features

1. **Add Task:** Users can add a new task by entering text in the input field and clicking the "Add" button.
2. **Edit Task:** Users can edit existing tasks by clicking the edit icon.
3. **Mark as Completed:** Clicking on a task marks it as completed (strikethrough). Clicking again unmarks it.
4. **Delete Task:** Users can delete a task by clicking the delete icon.
5. **Persistent Data:** Tasks are saved in the browser's local storage and will be available even after the page is reloaded.
6. **Responsive Design:** The app is designed to work well on both mobile and desktop devices.

## Technologies Used

- **HTML5** for structuring the web page.
- **CSS3** for styling the UI and creating a responsive design.
- **JavaScript** for application logic and interaction with local storage.
- **Font Awesome** for providing icons.
- **Google Fonts (Poppins)** for font styling.

## Project Structure

```bash
.
├── index.html      # Main HTML structure
├── script.js       # JavaScript for the to-do list logic
├── style.css       # CSS for the design and layout
└── README.md       # Project documentation
```

## Files Included

### 1. `index.html`

This is the main HTML file that structures the web page. It includes:

- A text input for adding new tasks
- A button to add tasks
- A section to display tasks
- Font Awesome icons for editing and deleting tasks

### 2. `script.js`

This JavaScript file manages the functionality of the To-Do List, including:

- Adding, editing, and deleting tasks
- Marking tasks as completed
- Saving tasks in local storage so that they persist across browser sessions

### 3. `style.css`

This CSS file defines the styles for the application, including:

- Layout and design of the task input form and task list
- Responsive styles for different screen sizes
- Animations for a more dynamic look

## How to Run

1. Clone or download the repository.
2. Open the `index.html` file in your browser to use the to-do list app.

## Local Storage Structure

Tasks are saved in local storage with the following key-value pair:

- **Key:** `count_taskname`
- **Value:** `boolean` (indicates whether the task is completed)
