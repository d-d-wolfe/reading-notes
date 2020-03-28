[Reading Notes Home](https://d-d-wolfe.github.io/reading-notes/)

# Class 01

## Introductory HTML and JavaScript

**HTML Basics**

*Process and Design*

- Decide who your target audience is, why they will come to your site, what they are looking for on your 
  site, and when they will visit again.

- Use a wireframe (a basic drawing of what the site should look like) to map out the high level design of
  the site.

- Create a sitemap to allow you to plan the structure.

- Designing a webpage is about communication. Showing "Visual Hierarchy" helps visitors understand what you
  are trying to communicate. In other words, areas that are larger or have a brighter color will draw the 
  visitor's eye to the things you want them to see first.

- Grouping and similarity help to simplify the information you are presenting.

*Structure*

- HTML pages are basically text documents that use tags (characters inside angle brackets) to give special
  meaning to the information they surround.

- Tags are also known as elements.

- Usually there is an opening tag and a closing tag, which denote the beginning and end of a piece of content.

- You can place attributes with an opening tag. Attributes tell us more about what that element contains.

- Attributes require a name and a value (i.e.: height="150")

- It is important to know what tags are available and what they do and where they can go in the structure.

*HTML5 Layout*

- In previous versions of HTML we used multiple <div> elements. The new elements included in HTML5, which indicate the purpose of different parts of a webpage, allow for clearer code.

- Older browsers, like Internet Explorer 8 (and older), that don't understand HTML5, need to be told which 
  elements are block-level elements. Extra JavaScript is needed to make HTML5 elements work, and you can find that code, for free, on Google.

*Extra Markup*

- DOCTYPES tell browsers which version of HTML you are using

- You can add comments to your code, that won't show on the webpage, by using <!-- -->.

- the id and class elements are used to identify particular elements, and the div and span elements allow you
  to group block-line and inline elements together.

- To cut a window into your web page that displays another page you can use iframes.

- You can supply all kinds of information about your webpage by using the meta tag.

- If you need to include special characters, on your webpage, that aren't generally on a keyboard, you can use 
  escape characters like <, > and &#169; 

**JavaScript Basics**

*Programming With JavaScript*

- How JavaScript (JS) makes web pages more interactive

  - Access Content - Use JS to select any element, attribute or text from
    an HTML page.
  
  - Modify Content - Use JS to add elements, attributes, or text to the page
    or remove them.

  - Program Rules - Specify a set of steps for the browser to follow (like
    a recipe), which allows it to access or change the content of a page.

  - React to Events - You can specify that a script should run when a 
    specific event has occurred.

*What is a Script and how do I write one*

- A script is a series of instructions that a computer can follow to achieve
  a goal. Similar to a recipe, handbook, or a manual.

- To write a script, state your goal and list the tasks that need to be 
  completed in order to achieve it.

- Start with the big picture and break that down into smaller steps.

    - Define the goal.

    - Design the script.

    - Code each step.

- Create a flowchart showing everey step that needs to be accomplished.

- Computers solve tasks differently than humans, so we need to learn to 
  "think" like a computer.

*Expressions and Operators*

- Expressions result in a single value. There are basically two types of 
  expressions.

  - Expressions that just assign a value to a variable.

  - Expressions that use two or more values to return a single value.

- Expressions rely on Operators; they allow programmers to create a single
  value from one or more values.
  - Arithmetic Operators such as +, -, /, *, ++, --, %.

  - String Operator - There is only one string operator; The + symbol. It
    is used to join the strings on either side of it.

*Functions*

- Functions allow you to group a series of statements together to perform a 
  specific task. If different parts of a script repeat the same task, you
  can reuse the function.

  - Declaring a function - To create a function, you give it a name and then
    write the statements needed to achieve its task inside curly braces. This
    is known as a function declaration.

  - Calling a function - Now that you've declare the function, you can 
    execute all of the statements between its curly braces with just one line of code. This is known as calling the function.

  - Sometimes a fiunction needs specific information to perform its task. In
    such cases, when you declare the function you give it parameters. Inside
    the function, the parameters act like variables.

  - When you call a function that has parameters, you specify the values it
    should use in the parentheses that follow its name. The values are called arguments, and they can be provided as values or variables. 