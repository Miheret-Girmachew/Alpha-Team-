Learning web development( HTML, CSS, and JavaScript)

Practice 1

Todo-List App Sample

This is a beginner-level application for a simple todo list. The application uses HTML, 
CSS, and JavaScript to create a basic user interface where users can add tasks to their
todo list.

# Table of Contents

-Features
-Check
-Usage
-DOM methods used
-License
-Functionality

## Features

The todo list app has the following features;

-User can add items to the todo list.
-user can delete items from the todo list.

##check

-To look and chech for the todo list app, follow these steps:

1. Clone the repository: git clone https://github.com/Miheret-Girmachew/todo-list.git
2. Navigate to the project directory: 
3. Open the file in the web browser.

## Usage

To use the todo list app, follow these steps:

1. Type the task you want to add into the button where it says add your tasks.
2. Click the add buttton if you have additional tasks to add.
3. Press the end button where the "add" option had been placed ,while being used to add tasks, to delete the tasks you have written.

## DOM Methods Used

- document.querySelector

## License

This project is licensed under the MIT license. See the LICENSE file for more details.

## Functionality

* HTML code

- The code indicates that the document type of the page is HTML5 with English as a document language.
- It has a title name Todo List which appears in the title bar of the browser.
- The code has a stylesheet relation with reference to the CSS file "todo.css" to apply style to the page.
- It has style tag where the background image of the page is set.
- It also has a main body part where all the visual elements are placed containing everything seen on the webpage.
- It has a division with class name of container used to center align and hold the other elements inside it.
- It contains an HTML tag with heading 1 of text " To Do List".
- Also has a division with id name of  "newtask" containing an input field  and add buttons to add new tasks. Also has an additional
 empty division  with an id name of "tasks" which is used later by JavaScript to make the page with a list of the user's Todo tasks.
- At the end it contains a script src of "todo1.js" to manipulate the elements in the HTML page and add functionality to the page.

** CSS code

 It appears to be responsible for creating a webpage with a container for tasks that can be added and deleted.
 - Body sets the height of the entire webpage to 100% viewport height. 
- It container defines a container element with a width of 650px and a height of 200px. It is positioned absolutely on the top right of the screen,
 centered vertically with transform:translate(0,-50%), and has a solid background color (#700c9f), a border radius of 10px, and a minimum width and 
height of 450px and 100px respectively. This element also has text aligned to the center. 
- #newtask refers to an element with an ID of newtask, which is relatively positioned. The element has padding on the top and bottom and on the left and right.
 This element has an input field for adding a task, styled with a background color (#d1d3d4), and font family (Poppins). When its focus is activated by a user,
 its outline color changes to #0d75ec. It also includes a button for submitting a new task, styled with a background color of #0d75ec, text color of white, a 
cursor property set to pointer, and it takes up 20% of available width alongside a height of 45px and rounded borders. 
- Task defines a class for individual tasks within the previously defined #tasks element. The task has rounded corners and a background-color of #c5e1e6, and 
a minimum height of 50px. Its font family is Poppins with a font-weight set to 500. This class further includes a button for deleting tasks with a background 
color of #6583e5, of text color white, rounded borders, and dimensions set to Width:40px; Height:100%.

*** JavaScript

- The JavaScript code defines an event listener on the onclick event of an HTML element with the id push. When this element is clicked, the function inside the curly
 braces {} will be executed.
-The code first checks if the length of the value of an input element with the id newtask is zero. If it is, an alert will be displayed asking the user to kindly enter
 a task name.
- If the length of the input value is not zero, the code creates a new div element with the class task. It sets the inner HTML of this new div element to a string that
 contains some text and two HTML elements: a span element and a button element. The text inside the span element is the value of the input element with the id newtask. The button element has a class delete and an icon to indicate that it will delete this task.
-The code then selects all elements with the class delete and sets an event listener on each element's onclick event. When any of these elements is 
the parent node (the div element with the class task) is removed from the HTML document using the remove() method.

