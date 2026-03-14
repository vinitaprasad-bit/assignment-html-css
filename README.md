# assignment-html-css
Vinita Prasad-assignment 1
This project is a simple personal portfolio website created using HTML and linked with an external CSS file for styling. The basic structure starts with the <html> tag, which is the root element of the webpage. Inside it, the <head> section is used to include metadata and external resources, while the <title> tag sets the browser tab name as "My Portfolio". The <body> section contains all the visible content of the website.

The code includes two <link> tags inside the body to connect external resources. One link connects the Google Fonts library to use the "Poppins" font family with different font weights (300, 500, 700). The second link connects an external CSS file named style.css, which is used to design and style the webpage layout, colors, fonts, and spacing.

The <header> section displays the main introduction of the portfolio. It contains an <h1> tag that shows the name "VINITA PRASAD" as the main heading and a <p> tag describing her as a BCA student passionate about learning web development. Below the header, a <nav> section is created to provide navigation links such as Home, About, Projects, and Contact. These links allow users to move between different sections of the same webpage.

The website is divided into multiple <section> elements with unique IDs like "home", "about", and "projects". The Home section includes a short introduction paragraph and a list of hobbies using an ordered list (<ol>) with list items (<li>), such as Dancing and Engaging with children. The About section contains a paragraph describing the student’s educational background and enthusiasm for learning new things. The Projects section (and other sections if included) is meant to display academic or personal projects.

Overall, this code represents a basic structured portfolio website using semantic HTML elements such as header, nav, and section. It demonstrates fundamental web development concepts including page structure, internal navigation using anchor tags, linking external stylesheets, and organizing content in a clear and readable format.

ASSIGNMENT- 2 (DESCRIPTION)
# Personal Portfolio Website

This project is a simple **Personal Portfolio Website** created using **HTML, CSS, and JavaScript**. The purpose of this project is to present basic information about the developer, showcase projects, and allow users to interact with the webpage.

## Features

### 1. Hobby Interaction Enhancements

The hobby section allows users to interact with the list dynamically.

* Users can add a new hobby benefit using an input box and an **Add button**.
* The entered text is added as a new item in the ordered list.
* Each list item contains a **Delete button** that allows the user to remove that item from the list.

### 2. Contact Form Interactivity

The website contains a simple **Contact Form** where users can enter their name, email, and message.
When the form is submitted, a **JavaScript alert message** appears confirming that the form has been submitted successfully.

### 3. Dynamic Footer

The footer of the webpage displays the **current date and time dynamically** using JavaScript.
The time updates automatically every second.

## Technologies Used

* HTML – For structuring the webpage
* CSS – For styling and layout
* JavaScript – For adding interactivity and dynamic behavior

## Project Sections

* Home
* About
* Projects
* Contact
* Dynamic Footer

## Purpose of the Project

This project was created as part of a **web development assignment** to practice the integration of **HTML structure, CSS styling, and JavaScript functionality** in a single webpage.
**ASSIGNMENT-3**
**Task 1: Find Second Largest Number**

This task focuses on finding the second largest number from a given array without sorting the array. An array of numbers is created and a loop is used to traverse through each element. During the iteration, two variables are maintained to store the largest and the second largest values. Whenever a number greater than the current largest value is found, the previous largest value becomes the second largest. If the number is smaller than the largest but greater than the second largest, it replaces the second largest value. This approach helps in efficiently finding the second largest number in a single pass through the array without using any sorting method. The final result is displayed on the webpage.

---

**Task 2: Return Unique Elements**

This task involves creating a function that takes two arrays as input and returns a new array containing only the unique elements from both arrays. The arrays are first combined together, and then a loop is used to check each element. If the element is not already present in the new array, it is added to it. This ensures that duplicate values are removed and only unique elements remain. The final array with unique values is then displayed as the output.

---

**Task 3: Student Score Analysis**

In this task, an array of student objects is created where each object contains the student's name, age, and an array of their scores. A function is implemented to calculate the average score for each student by adding all the scores and dividing by the number of subjects. After calculating the averages, the program compares them to determine which student has the highest average score. Finally, the program logs and displays the top student along with their average score.

---

**Task 4: Countdown Timer**

This task involves building a one-hour countdown timer using HTML, CSS, and JavaScript. The timer displays time in minutes and seconds (MM:SS format). Buttons are provided to start, pause, and reset the timer. JavaScript is used to control the timer logic using functions and intervals. The timer counts down every second until it reaches zero, and it prevents the timer from going into negative values. When the countdown reaches zero, a message is displayed to inform the user that the time is up.

**assignment-4**
This project implements an interactive Frequently Asked Questions (FAQ) section using HTML, CSS, and JavaScript with an object-oriented approach. HTML provides the basic page structure and a container where all questions and answers are dynamically inserted. CSS is used to design the layout and hide answers by default while adding visual cues like “+” and “−” icons for expansion and collapse. JavaScript defines a QAItem class that stores each question and answer and contains a method to render them into HTML elements. Event listeners are attached to each question so that when the user clicks it, the corresponding answer toggles its visibility. The questions and answers are stored in an array of QAItem objects, allowing the FAQ section to be dynamically generated and easily extended.

