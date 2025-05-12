# Javascript Certification Mid-Level Training Course
Course Link: https://certificates.dev/javascript/dashboard/training/js-level-2-training

## Chapter 0: Start here
### Welcome
- Hello there! We are thrilled to have you on board as you embark on this exciting journey to get your JavaScript expertise certified.
- This program is designed to provide you with a comprehensive and structured approach to practicing your JavaScript skills and getting familiar with the structure of the official JavaScript exams.
- The program is organized into 9 chapters.
- The first 8 chapters consist of lessons, pop quizzes, and coding challenges.
- Each lesson contains a list of resources that are carefully curated to help you understand and master key JavaScript concepts.
- At the same time, the pop quizzes and coding challenges provide you with opportunities to test your knowledge and reinforce what you've learned.
- We recommend that you start with the first lesson and work your way through the program in sequential order.
- This will help you build a solid foundation of knowledge and skills you can draw upon as you progress through the program.
- We also encourage you to take advantage of the downloadable coding challenges, which are designed to give you hands-on experience with JavaScript development.
- These challenges will help you apply what you've learned and develop a deeper understanding of using JavaScript in real-world scenarios.
- Finally, the last chapter of the program consists solely of coding challenges, which will allow you to put your skills to the test and showcase your proficiency as a JavaScript developer.
- The format of the Chapter 9 challenges is designed to be very similar to the coding challenges of the final exams.
- If you face any technical issues or have suggestions for improvements as you go through the preparation material you can let us know by clicking the “Submit Feedback” link at the top of the site.
- For technical questions or discussions, you can communicate with the JavaScript Certified community of developers on Discord. (You can accept your invite in your email if you haven't already).
- We hope that you find this program engaging and rewarding, and we wish you all the best as you work towards becoming a certified JavaScript developer!

Sincerely, the certificates.dev team

### What Do I Need?
To follow the JavaScript Developer Certification Training, you will need to have the following setup on your computer:
1. Node.js
    - Node.js is an open-source, cross-platform JavaScript runtime environment that executes JavaScript code outside of a web browser.
    - The code challenges in the JavaScript Developer Certification Program require Node.js LTS.
    - You can download and install Node.js by following the instructions provided on their official website
    - [Node.js](https://nodejs.org/en)
2. NPM
    - npm is a package manager for Node.js and is used to install dependencies and manage packages. It is included with the the node.js download.
3. Editor
    - The recommended code editor for the JavaScript Developer Certification Program is Visual Studio Code (VS Code). VS Code is a lightweight and versatile code editor that provides a wide range of features and extensions for Vue.js development.
    - You can download and install VS Code by following the instructions provided on their official website:
    - [Visual Studio Code](https://code.visualstudio.com/)
- During the actual exam, you’ll be using an embedded IDE powered by StackBlitz. If you’d like to try out working in that editor to help prepare for the exam you can do so on their website.
- Once you have installed these tools, you will be ready to start the JavaScript Developer Certification Training. If you encounter any issues during the setup process or while working through the program, please do not hesitate to reach out to the Discord community or our support team for assistance.

### How to Startup the Coding Challenges
Throughout the training you’ll download coding challenges to your local machine. These are the steps you should follow to run each challenge:
1. Ensure you have all the pre-requisite software installed from the previous lesson
2. Download the challenge from the training platform
3. Unzip the challenge folder
4. Open the folder in your IDE (we recommend [Visual Studio Code](https://code.visualstudio.com/))

#### Serve the Website that the JavaScript Runs In
1. Using your IDE’s built-in terminal or your regular terminal at the challenge directory, install project dependencies with the following command:
```
> npm install
```
2. Start up the local dev server with the following command:
```
> npm run dev
```
3. Visit the url output in the terminal after running the command to see the site. (Usually http://localhost:5173 if that port isn’t already in use.)
4. That’s it! You can work in the project files like normal to meet the requirements of the challenge

#### Why?
> Why are coding challenges served this way? Why don’t we just open `html` files directly in the browser and link the related JavaScript files with a `script` tag?
- The reason for the later steps above is because all coding challenges use [Vite under the hood](https://vitejs.dev/) to provide a dev server with Hot Module Reloading.
- This means you’ll see your code changes immediately upon file save in the browser without having to refresh the webpage. 🎉

## Chapter 1: JavaScript Fundamentals
### Intro to JavaScript
- JavaScript is the programming language of the web browser and can also be found on web servers, IoT devices, and more.
- For this exam, you should be familiar with both the basics of JavaScript and more intermediate concepts.
- This chapter gives a refresher of the basics. If you are comfortable with the concepts in chapter 1 already, feel free to skip it.
- If you find yourself struggling through this chapter, consider starting with the level 1 exam instead of this one.
- You can find a link to it on the root training page of the dashboard.
- [MDN Docs > What is JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
- [JavaScript.info > An Introduction to JavaScript](https://javascript.info/intro)
- [JavaScript.info > Hello, world!](https://javascript.info/hello-world)
- [JavaScript.info > Code Structure](https://javascript.info/structure)
- [MDN Docs > A First Splash into JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash)

### Basic Debugging
- `console.log` is a simple tool for giving you visibility into your JavaScript code as it runs.
- It’s the easiest way to start seeing what’s going on with your code but it’s also a powerful debugging tool that experts use everyday.
- The console is where you’ll view messages logged by `console.log` as well as error messages thrown by JavaScript.
- During the exam, you should know simple issues you might face writing JavaScript and how you can fix those issues using the console and `console.log`.
- [MDN > What Went Wrong](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)
- [Geeks for Geeks > Console.log](https://www.geeksforgeeks.org/javascript-console-log-method/)
- [JavaScript.info > Developer Console](https://javascript.info/devtools)

### Challenge 1: Fix the Syntax Error And Log a Custom Message to the Console
- [Link to Challenge](./challenge1/README.md)

### Variables and Data Types
- Variables are like containers where you can store and label different types of information.
- That information can be a string of characters like those that makeup your name or a number that can be used in Math equations, like your age, or a variety of other types.
- During the exam you’ll need to know the various ways of declaring variables with `let` and `const`.
- You’ll also need to be familiar with primitive data types like strings, numbers, and booleans.
- Later on we’ll also discuss more complex types, like arrays and objects.
- [MDN > Storing the information you need — Variables](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Variables)
- [JavaScript.info > Variables](https://javascript.info/variables)
- [JavaScript.info > Data types](https://javascript.info/types)
- [MDN > Handling text — strings in JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Strings)
- [MDN > Useful string methods](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Useful_string_methods)

### Challenge 2: Declaring Variables
- [Link to Challenge](./challenge2/README.md)

### Basic Operators
- For the exam, you should know how to use operators to perform match operations and comparisons.
- [MDN > Basic math in JavaScript — numbers and operators](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Math)
- [JavaScript.info > Basic Operators, maths](https://javascript.info/operators)
- [JavaScript.info > Comparisons](https://javascript.info/comparison)

### Challenge 3: Space Explorer Game - Operators
- [Link to Challenge](./challenge3/README.md)

### Arrays
- Arrays allow us to store lists of data.
- For example, a list of products to display on an e-commerce site or a list of news articles to browse through.
- For the exam, you should know the basics of working with arrays; things like: getting array length, adding new items to arrays, accessing an item at a specific index, removing items from arrays, and more.
- For this exam, you’ll also need to know advanced array methods but we’ll cover that in the Advanced Array and Object Methods chapter.
- [MDN > Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- [JavaScript.info > Arrays](https://javascript.info/array)
- [JavaScript.info > Array Methods](https://javascript.info/array-methods)

### Challenge 4: Virtual Garden Manager - Arrays
- [Link to Challenge](./challenge4/README.md)

### Control Structures
- Conditionals are how we give our code the ability to make decisions based on the values of our variables.
- Loops are useful for doing the same thing over and over again.
- [MDN > Making decisions in your code — conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
- [JavaScript.info - Conditional Branching](https://javascript.info/ifelse)
- [JavaScript.info - Logical operators](https://javascript.info/logical-operators)
- [MDN > Looping code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
- [JavaScript.info - Loops: while and for](https://javascript.info/while-for)
- [JavaScript.info - The “switch” statement](https://javascript.info/switch)

### Challenge 5: Number Analyzer - Control Structures
- [Link to Challenge](./challenge5/README.md)

### Functions
- Functions allow you to store a piece of code that does a single task inside a defined block, and then call that code whenever you need it using a single short command — rather than having to type out the same code multiple times.
- Learn the various syntaxes for defining functions, how to call functions, and how to make them flexible with artuments.
- [MDN > Functions — reusable blocks of code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)
- [MDN > Function return values](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Return_values)
- [JavaScript.info > Functions](https://javascript.info/function-basics)
- [JavaScript.info > Function expressions](https://javascript.info/function-expressions)
- [JavaScript.info > Arrow functions, the basics](https://javascript.info/arrow-functions-basics)

### Challenge 6: Wizard's Spellbook - Functions
- [Link to Challenge](./challenge6/README.md)

### Objects
- Objects are data structures used for grouping variables (properties) together with related functions (methods).
- [MDN > JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
- [JavaScript.info - Objects](https://javascript.info/object)
- [JavaScript.info - Object references and copying](https://javascript.info/object-copy)

### Challenge 7: Virtual Pet Sanctuary - Objects
- [Link to Challenge](./challenge7/README.md)
