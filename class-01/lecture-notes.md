# Lecture Notes: Class 01

- Due Dates in Canvas
  - Retros are always due by midnight the same day they are assigned.
    - I want you to reflect on your most recent learning and have that fresh in your mind.
    - these CANNOT be late
  - Readings are due right before class starts
    - readings are assigned the same day as the labs
      - except for the Regex101 reading...
    - there is no penatly for turning in a late reading assignment
  - Code Challenges and Labs are due no later than the start of the next class day
    - EXAMPLE: Monday/Tuesday's CC & Labs will be due no later than Thursday at 6:30pm.
    - EXAMPLE: Thursday/Saturday's CC & Labs will be due no later than Monday at 6:30pm.
  - Career Assignments
    - Turn these in whenever you can.
    - You will not lose points for late submissions on these.
    - HOWEVER, do NOT fall behind and have a bunch of Career Assignments due at the end of the 9 weeks.
  - Feedback Assigments
    - due every week by Sunday midnight.
    - I suggest you complete the Feedback assignment on Saturdays.
    - Please do not skip these!
      - They are easy points!
      - We take your feedback VERY seriously and discuss it among the instructional staff every single week.

- What's new in 301?
  - Floor 3 in Remo
  - Warm-ups
    - multiple languages
  - Code Challenges
    - 6-10ish short word problems/algorithms
    - see shred talks if you learn well from video demo
    - first introduction to formal testing and TDD
      - TDD = Test Driven Development
    - practice for interviews
      - a tiny stepping stone to whiteboard interview
  - More Paired Programming!
  - Career Coaching
    - More career assignments
  - Lab Assignments
    - Trello for a lot of weekly project work flow
  - Grading standards
    - Turn in your Labs and Retros!
    - Take care of your TAs by following instructions posted by Phil every week in Slack
    - Resubmissions allowed up until Project Week(s) start

- Classes
  - Classes are the building blocks for React
    - They are part of ES6 and allow for Object Oriented Programming
  - A blueprint for creating objects
    - A system where we can define objects in relation to each other using subclasses using the keyword extends.
  - [Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes) on MDN

- Arrow Functions
  - multiple ways to create a function
    - mostly been doing function declarations in 201
    - function expresions are another way and arrow functions are one way to write a function expression
  - function expression vs. declaration
    - Function declarations load before any code is executed while Function expressions load only when the interpreter reaches that line of code.
    - Similar to the var statement, function declarations are hoisted to the top of other code. Function expressions aren’t hoisted, which allows them to retain a copy of the local variables from the scope where they were defined.
    - benifits of function expressions
      - in closures - <https://www.youtube.com/watch?v=qikxEIxsXco>
      - as an argument to another function
      - to immediately invoke your function
  - allow us to write concise one line functions
  - the contextual this is not bound to the function if you use an arrow function, it will bubble up to the next non-arrow function

- React and Component-Based UI
  - <https://www.w3schools.com/REACT/DEFAULT.ASP>
  - Why?
    - React is hugely in demand in the industry
    - Component based architecture is easier to test and reuse
    - dynamicly updates application state without requiring a page reload
    - dev advantages
      - reusable parts
      - separation of concerns
  - What?
    - React (angular and vue) are component based libraries that allow us to build applications using this technique
    - Bind state/data to the DOM, they update the dom for us!!
      - react rerenders content when state changes by using a Virtual DOM
    - We treat components like they are html elements `<Header />`
    - Modularity
      - each component is it's own module, or block of code, that we can make available in another component
      - export the component from it's file, and import it where you want to use it
        - you can also import css and other files to a component module
  - How
    - WRRC
      - a request is made in the address bar for our website resource and the files are served
      - who is the client, who is the server?
    - Use `npx create-react-app <application_name>` to start your project
    - refer to the reactAppRemove.md if you want to clean up the file structure before you start
    - JSX (syntax extension) allows us to write html markup in javascript
  - to start your React server
    - `npm start`
  - to close down your React server
    - control + c

- Shred Talks & Code Challenges
  - Daily "Shred Talks" will introduce you to a new javascript coding concept, setting you up to complete the daily "Code Challenge" series.
  - Make sure you are in the `javascript` folder of your DSA repo before running any javascript commands in the terminal.
  - Don't forget to work on a new branch!
  - Don't forget to pull down the new challenges!
    - `npm run get-challenge 01`
    - You only need to run this command ONCE to grab all of the Code Challenges for this assignment.
  - Check out the `how-to-solve-a-code-challenge.md` file for tips and tricks on how to break down a code challenge and solve it.

- `Array.forEach()` Demo in Repl.it
  - <https://replit.com/@HexxKing1/301n25-Code-Challenge-forEach#index.js>
