---
theme: penguin
title: 📺 Introduction to JavaScript
layout: intro
---
# 📺 JavaScript

Introduction and General concepts <br>
by Rodolfo Roman

---
---
# 📺 Introduction to JavaScript

👋 Welcome to the video on the fundamentals of JavaScript, an essential programming language in web development. 

🌐 JavaScript is the backbone of modern web development, allowing developers to create dynamic and interactive websites. In this video, we'll cover the basics of JavaScript, its syntax, and its importance in web development.

---
---
# 🚀 Overview of JavaScript as a programming language

📝 JavaScript is a high-level, interpreted programming language that enables dynamic and interactive functionality on web pages.

✨ **Key Features:**
- 🧱 Object-oriented programming
- ⚡️ Event-driven programming
- 🔄 Prototypal inheritance
- 🌐 Cross-platform compatibility

---
layout: text-window
reverse: true
---
# 💻 Syntax of JavaScript

📝 In JavaScript, code is written using a specific syntax. The example above declares a variable called greeting and assigns it the value "Hello, world!". The console.log() function is then used to display the value of the greeting variable in the browser console.

::window::
```javascript
const greeting = 'Hello There!'
console.log(greeting)
```

---
---
# 💻 Syntax of JavaScript - cont.

🔑 Key Components:

- 📦 Variables
- 🔧 Functions
- 📜 Statements
- ➕ Operators
- 🗃️ Data types

---
---
# 🎉 Benefits of JavaScript

🌟 JavaScript offers numerous benefits that make it an indispensable language in web development.

1. 💡 Enhances user experience through interactive elements.
2. 🔄 Allows for dynamic content manipulation.
3. ✅ Validates form data on the client-side.
4. 🌐 Enables asynchronous communication with servers (AJAX).
5. 🧩 Supports modern frameworks and libraries (React, Angular, etc.).

---
---
# 🌐 Importance and Applications of JavaScript in Web Development

📝 JavaScript plays a crucial role in web development, both on the client-side and server-side.

💼 **Client-Side Scripting:**
- 🔧 Manipulating web page elements.
- 🔒 Validating form data.
- 🎯 Creating interactive features (sliders, tabs, etc.).
- 🎞️ Implementing animations and effects.

---
---
# 🌐 Importance and Applications of JavaScript in Web Development - cont.
🖥️ **Server-Side Scripting:**
- ⚡️ Node.js: JavaScript on the server-side.
- 📡 Handling HTTP requests and responses.
- 🚀 Building scalable and real-time web applications.
- 🗄️ Accessing databases and external APIs.

---
---
# 🌐 Importance and Applications of JavaScript in Web Development - cont.
📝 **JavaScript has a vast ecosystem of libraries and frameworks that simplify and streamline web development.**

🔥 **Some popular examples:**
- ⚛️ React: Building user interfaces.
- 🔺 Angular: Full-featured web application framework.
- 🖼️ Vue.js: Progressive JavaScript framework.
- ⚡️ Express.js: Minimalist web application framework for Node.js.
- 💡 jQuery: Simplifies DOM manipulation and AJAX.

🚀 These libraries and frameworks save developers time and effort by providing pre-built components, efficient rendering, and simplified syntax.

---
layout: new-section
---
# 📚 Javascript Variables
 ![working](https://media.giphy.com/media/3oriePtJwgFRRe8JTW/giphy.gif)

---
layout: text-image
media: 'https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif'
---
# 📚 Javascript Variables

## Definition and Purpose of Variables in Programming

📦 Variables are named containers used to store data in programming languages. 

🔄 They allow us to store values that can be accessed and manipulated throughout the program.

---
---
# 📚 Javascript Variables - cont.

## Declaring and Initializing Variables

📝 To declare a variable, we use the `var`, `let`, or `const` keyword.
  
🎁 Initializing a variable means giving it an initial value.

🚀 We can declare and initialize a variable in a single line.

```js
// Declare then Assign
let age
age = 25

// Declera and Assign
let name = John
```
---
---
# 📚 Javascript Variables - cont.

## Naming Conventions for Variables

📛 Variables should have meaningful and descriptive names.

🐍 Use camelCase, like `userName`, or snake_case, like `total_amount` for multi-word variable names.

❌ Variables cannot start with numbers or special characters, except `_` and `$`.

---
---
# 📚 Javascript Variables - cont.

## Variable Scope and Hoisting

- Scope determines the visibility and accessibility of variables. 🔍
- Variables can have global or local scope.

- Hoisting is a JS behavior where variables are moved to the top of their scope during compilation. 📤

```javascript
console.log(age) // Output: undefined
var age = 30;
```

🌟 Now you know the basics of JavaScript variables! 🌟

---
layout: new-section
---
# JavaScript Data Types
![full-choices](https://media.giphy.com/media/4RYU6oCqCFMiD8e9G5/giphy.gif)

---
---
# JavaScript Data Types - cont.
## Numbers 👉

- Working with numerical data
  - Example: `let age = 25;`
- Mathematical operations with numbers
  - Example: `let sum = 10 + 5;`
- Understanding number precision and limitations
  - Example: `let num = 0.1 + 0.2;`

---
---
# JavaScript Data Types - cont.
## Strings 👉

- Definition and manipulation of text data
  - Example: `let message = 'Hello, World!';`
- String concatenation and interpolation
  - Example: 
```javascript
let name = 'John'
let greeting = `Hello, ${name}!` // Output: Hello, John
```

- Common string methods and operations
  - Example:
```javascript
let sentence = 'The quick brown fox'
let length = sentence.length
```

---
---
# JavaScript Data Types - cont.
## Booleans 👉

- Introduction to logical values (true and false)
  - Example: `let isLogged = true;`
- Boolean operators (AND, OR, NOT)
  - Example:
```javascript
let hasPermission = true
let isAdmin = false
let canAccess = hasPermission && isAdmin 
// canAccess = false
// && is an AND Operator
```

---
---
# JavaScript Data Types - cont.
## Booleans 👉
- Logical conditions and decision-making
  - Example:
```javascript
let age = 18;

if (age >= 18) {
  console.log('You are an adult.') 
} else {
  // Never executed because age is not less than 18
  console.log('You are not yet an adult.') 
}

// Output: You are an adult.
```

---
---
# JavaScript Data Types - cont.
## Arrays 👉

- Storing and accessing multiple values in an ordered manner
  - Example: `let numbers = [1, 2, 3, 4, 5];`
- Array methods and operations (e.g., adding, removing, searching)
  - Example:
```javascript
let fruits = ['apple', 'banana', 'orange']

fruits.push('grape') 
// fruits = ['apple', 'banana', 'orange', 'grape']

let bananaIndex = fruits.indexOf('banana')
// bananaIndex = 1, the indexes starts at 0

```

---
---
# JavaScript Data Types - cont.
## Objects 👉

- Key-value pairs and object literals
  - Example:
```javascript
let person = {
  name: 'John',
  age: 25,
  city: 'New York'
}
```

---
---
# JavaScript Data Types - cont.
## Objects 👉

- Object properties and methods
  - Example:
```javascript
let person = {
  name: 'John',
  age: 25,
  greet: function() {
    console.log(`Hello, my name is ${this.name}.`);
  }
}

person.greet() // Output: Hello, my name is John
```

---
---
# JavaScript Data Types - cont.
## Objects 👉

- Accessing and modifying object data
  - Example:
```javascript
let person = {
  name: 'John',
  age: 25,
  city: 'New York'
}

person.age = 26

let cityName = person.city
```

---
layout: new-section
---
# JavaScript Operators
![full-choices](https://media.giphy.com/media/3owzW5c1tPq63MPmWk/giphy.gif)

---
---
# JavaScript Operators - cont.
## A. Arithmetic Operators

- Addition, subtraction, multiplication, division
  - Example: `let sum = 10 + 5;`
- Modulus and exponentiation operators
  - Example:
```javascript
let remainder = 10 % 3 // remainder = 1

let result = 2 ** 3 // result = 8
```

- Order of operations (precedence)
  - Example:
```javascript
let result = (10 + 5) * 2

// result = (15) * 2 = 30
```

---
---
# JavaScript Operators - cont.
## C. Logical Operators

- Combining and manipulating boolean values
  - Example: `let result = true && false;`
- AND, OR, and NOT operators
  - Example: 
```javascript
let condition1 = true
let condition2 = false
let result = condition1 || condition2 // OR
```
- Short-circuit evaluation
  - Example: 
```javascript
let value = null
let result = value || 'default' // result = 'default'
```

---
---
# JavaScript Operators - cont.
## D. Assignment Operators

- Assigning values to variables
  - Example: `let x = 10;`
- Compound assignment operators (e.g., +=, -=)
  - Example: 
```javascript
let count = 5

count += 2 // count = 5 + 2
```

---
---
# JavaScript Operators - cont.
## E. Other Operators (briefly mention)

- Increment and decrement operators
  - Example: 
```javascript
let count = 0

count++ // count = 1
```

- Ternary operator (conditional operator)
  - Example: 
```javascript
let age = 18

let isAdult = age >= 18 ? true : false
// isAdult = true, because age is >= 18
```

---
---
# 🎓 Conclusion

🔍 JavaScript is a fundamental programming language for web development. It enables dynamic and interactive web experiences, form validation, server-side scripting, and building powerful web applications.

🌟 Keep exploring and learning JavaScript! Whether you want to build interactive websites, develop server-side applications, or dive into popular frameworks like React or Angular, JavaScript offers endless possibilities.

🙏 Thank you for watching this presentation! If you found it helpful, any question or doubt, don't hesitate to reach me.

---
---
# 🔗 Additional Resources

📚 Here are some recommended resources to further your learning journey in JavaScript:

- 📖 **Books**:
  - <fancy-link href="https://eloquentjavascript.net/">"Eloquent JavaScript" by Marijn Haverbeke</fancy-link>
  - <fancy-link href="https://www.oreilly.com/library/view/javascript-the-good/9780596517748/">"JavaScript: The Good Parts" by Douglas Crockford</fancy-link>
  - <fancy-link href="https://github.com/getify/You-Dont-Know-JS">"You Don't Know JS" series by Kyle Simpson</fancy-link>

- 🌐 **Online Tutorials**:
  - <fancy-link href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript">MDN Web Docs (Mozilla Developer Network)</fancy-link>
  - <fancy-link href="https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/">freeCodeCamp</fancy-link>
  - <fancy-link href="https://www.w3schools.com/jsref/default.asp">W3Schools</fancy-link>

---
---
# 🔗 Additional Resources - cont.

- 🎓 **Online Courses**:
  - <fancy-link href="https://www.udemy.com/">Udemy</fancy-link>
  - <fancy-link href="https://www.coursera.com/">Coursera</fancy-link>
  - <fancy-link href="https://www.codecademy.com">Codecademy</fancy-link>
  - <fancy-link href="https://www.pluralsight.com">Pluralsight</fancy-link>

- 📚 **Official Documentation**:
  - <fancy-link href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">Mozilla Developer Network (MDN)</fancy-link>

---
---
# 🔗 Additional Resources - cont.

- 💬 **Community Forums**:
  - <fancy-link href="https://stackoverflow.com/">Stack Overflow</fancy-link>
  - <fancy-link href="https://www.reddit.com/r/learnjavascript/">Reddit r/learnjavascript</fancy-link>

Remember, practice and hands-on experience are key to mastering JavaScript. Keep coding, exploring, and utilizing these resources to deepen your understanding of JavaScript!

Thank you for reading, and happy coding everybody!
