[Reading Notes Home](https://d-d-wolfe.github.io/reading-notes/)

**Objects and Document Object Model**

**Objects**

- An *object* is a series of variables and functions that represent something from the world around us.

- In an *object*, variables are known as *properties* of the object, and functions are known as *methods* of the object.

- Literal notation is the most common way to create objects.

- You can access properties or methods of an object using *dot notation* or *square brackets*. (dot notation example: var holetName = hotel.name) (square bracket example: var hotelName = hotel['name'])

**Document Object Model (DOM)**

- The DOM is also referred to as Application Programming Interface (API).

- The browser represents the page using a DOM tree.

- DOM trees have four types of nodes:
  
  - Document Nodes

  - Element Nodes

  - Attrribute Nodes

  - Text Nodes

- You can select element nodes by their *id* or *class* attributes, by tag name, or using CSS selector syntax.

- Whenever a DOM query can return more than one node, it will always return a *NodeList*.

- From an element node, you can access and update its content using properties such as *textContent* and *innerHTML* or using DOM manipulation techniques.

- An element node can contain multiple text nodes and child elements that are siblings of each other.

- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using *jQuery*).

- Browsers offer tools for viewing the DOM tree.