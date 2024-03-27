# Simple DOM Todo App

This is a simple Todo application built using HTML, CSS, and JavaScript. It allows users to input tasks and add them to a list of todos.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [License](#license)

## Introduction
This application provides a minimalistic interface for managing todos. It allows users to input tasks and dynamically add them to a list. Additionally, users can remove tasks by clicking on them.

## Features
- **Add Todo:** Users can input tasks and add them to the list by clicking the "Click me" button.
- **Remove Todo:** Users can remove tasks from the list by clicking on them.
- **Responsive Design:** The application has a simple responsive design suitable for various screen sizes.

## Usage
1. Open the `index.html` file in a web browser.
2. Input a task in the text field provided.
3. Click the "Click me" button to add the task to the list.
4. To remove a task, simply click on it in the list.

## How it Works
- When the user inputs a task and clicks the "Click me" button, the `addTodo` function is called.
- This function creates a new `<p>` element containing the task text and appends it to the list of todos.
- To remove a task, the user clicks on the task text in the list. This triggers the `click` event listener, which removes the clicked task from the list.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
