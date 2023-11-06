![detective](https://github.com/nayaba/pw-lesson-02/assets/9198401/9e3b6399-a9c2-465b-b046-c8e0903a6743)

# The JavaScript Console: Your Coding Diary

Imagine you're a detective trying to solve a mystery, and you've got this neat little notebook where you jot down clues as you find them. The JavaScript console is kind of like that notebook for coders. It's a part of web browsers that lets you record information, test snippets of code, and uncover the mysteries of your JavaScript.

### Using the Console in CodePen

In CodePen, you don’t have to wear a trench coat to find the console. It's built right in.

1. Look for the "Console" tab at the bottom of the CodePen editor.
2. Click it open and behold — a wild console appears!

This console is where you'll see messages, errors, or any output from your code.

### `console.log()`: Chit-Chat with Your Code

Now, `console.log()` is your bread ![Uploading detective.gif…]()
and butter for sending messages to the console. It's like leaving yourself notes or sending texts to future you.

```javascript
console.log("Hello, CodePen!");
```

When you write this in the JavaScript panel on CodePen and run your Pen, "Hello, CodePen!" will show up in the console. It's a simple way to check if your code is working without affecting the visual part of your Pen.

### Why `console.log()` is Your New Best Friend

- **Debugging**: When your code doesn't do what you expect, `console.log()` helps you peek under the hood.
- **Learning**: Seeing the output of your code in real time helps you understand how JavaScript works.
- **Checking Values**: Not sure what value a variable has at a certain point? Log it!

### A Quick Example

Let's say we have a simple function that adds two numbers:

```javascript
function addNumbers(a, b) {
  console.log("Adding numbers...");
  return a + b;
}

let result = addNumbers(5, 7);
console.log("The result is:", result);
```

In CodePen's JavaScript panel, this would show "Adding numbers..." and "The result is: 12" in the console.

### Practice Using `console.log()`

Give it a try yourself! Go to CodePen, open the console, and write your first `console.log()` statement. Then, create variables, functions, or any operation and log their outcomes. You'll see how it prints out the values, making it easier to follow along with what your code is doing.

As you embark on your coding journey, `console.log()` is like the friendly guide who points out all the landmarks. It's crucial because it gives you instant feedback on what's happening in your code, which is invaluable when you're learning. So go ahead, log all the things, and watch the mysteries of your code unravel in the console.

##  Introduction to JavaScript as a Standalone Language

![what](https://github.com/nayaba/pw-lesson-02/assets/9198401/086a4d1e-382c-4c3f-b2e3-2f3b9e956ba4)

#### Understanding JavaScript's Flexibility

JavaScript is a versatile language that can be used in various environments. While it's commonly associated with web development in combination with HTML and CSS, it can also run independently on the command line (aka in the [Terminal](https://github.com/nayaba/pw-dev-tools#the-terminal-your-command-center)), or on a server, using environments like Node.js. This lesson focuses on JavaScript itself, not its interaction with HTML and CSS.

#### The JavaScript Engine

- **What is it?** A JavaScript engine is a program that executes JavaScript code. Every major web browser has its own engine, for example, Google Chrome has V8.
- **Node.js**: This is a runtime that allows you to run JavaScript on a server or your local machine's command line.

#### Writing JavaScript Without HTML/CSS

- **Standalone Scripts**: You can write and execute JavaScript without a browser, using just a text editor and a JavaScript runtime like Node.js.
  
#### Basic JavaScript Elements

1. **[Syntax](https://github.com/nayaba/pw-lesson-03)**: The set of rules that define the combinations of symbols that are considered to be correctly structured JavaScript programs.

2. **[Comments](https://github.com/nayaba/pw-lesson-03#comments-your-codes-sidekick)**: Notes that explain the code and are ignored when running it.

3. **[Variables](https://github.com/nayaba/pw-lesson-04)**: Containers for storing data values. In modern JavaScript, `let` and `const` are used to declare variables.

4. **[Data Types](https://github.com/nayaba/pw-lesson-05)**: JavaScript has various data types, including:
   - **Strings**: Textual data
   - **Numbers**: Both integers and floating-point numbers
   - **Booleans**: True or false values
   - **Objects**: Complex data structures
   - **Arrays**: Lists of data

5. **[Operators](https://github.com/nayaba/pw-lesson-06)**: Symbols that tell the interpreter to perform specific mathematical or logical manipulations.

6. **[Control Structures](https://github.com/nayaba/pw-lesson-07)**: Direct the flow of the program based on conditions.


7. **[Functions](https://github.com/nayaba/pw-lesson-08)**: Blocks of code designed to perform a particular task, called upon by name.


[Back to the Wiki](https://github.com/nayaba/pw-wiki)
