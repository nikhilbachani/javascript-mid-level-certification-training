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
