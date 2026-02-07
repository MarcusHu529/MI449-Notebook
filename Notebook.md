# MI449: Class Notebook

> **Name:** Weihang Hu  
> **Current Status:** Week 4    
> **Last Update:** 2/26/2026

---

## Weekly Notes

<details>
<summary><strong>Week 4: APIs & Architecture</strong></summary>

### Class Notes
- Missed class this week due to sickness.

### Reading Notes:

<details>
<summary><strong> What is an API (application programming interface)?</strong></summary>

- **APIs:** A set of rules enabling apps to communicate.
    - **Key Benefits:**
        - Simplifies development.
        - Integrates data/services from other apps.
        - Securely makes data/functions available.
        - Share only the necessary data and functions.
        - 
- **How do APIs work:** The bridge that connects client and server
    -  **Example:**
        - When purchase a product on an website, the site ask user to pay with paypal, which is a function that relies on APIs to make a connection.
            1. Buyer clicks payment button, a request is created to retrieve information from an application to the web server through the API's Uniform Resource Identifier (URI) and includes a request verb, headers, and sometimes, a request body.
            2. After receiving a valid request, the API calls the payment system
            3. The server sends a response to the API with requested info
            4. The API transfers the data to the product website to finish the payment process
    - Seamless connection
</details>

<details>
<summary><strong>Types of APIs</strong></summary>

- **Web APIs:** enable the transfer of data and functionality over the internet using HTTP protocol.
    1. Open APIs (aka Public APIs)
        - Open-source interfaces accessible via the HTTP protocol.
        - Strictly defined endpoints and request/response formats.
        - Publicly available for developers to integrate.
    2. Partner APIs
        - Connects strategic business partners. 
        - Self-service via a public developer portal.
        - Restricted access; requires onboarding and login credentials (Authentication).
    3. Internal APIs
        - Hidden, strictly internal use only.
        - Improve productivity and communication between internal dev teams.
        - Not available to external users or partners.
    4. Composite APIs
        - Combine multiple data or service APIs.
        - Access several endpoints in a single call.
        - Microservices architecture (where one task needs info from many sources).
    5. Other types of APIs
        - Data APIs: connect applications and database management systems.
        - Operating system APIs: define how apps use operating system services and resources.
        - Remote APIs: used to define how applications on different devices interact.
</details>

<details>
<summary><strong>Working with JSON</strong></summary>

- **JSON Basics:** a text-based data format following JavaScript object syntax.
    - A standard, text-based format for representing structured data.
    - Based on JavaScript object syntax but is language independent.
- **Structure & Syntax**
    - Supports strings, numbers, arrays, booleans (true/false), and null.
    - Strings and property names must use double quotes
    - JSON can be a single object or an array of objects.
    - Restrictions:
        - No trailing commas allowed.
        - No functions or methods allowed (data only).
        - No comments allowed.
- **Methods**
    - JSON.parse()
        - Converting a raw JSON string received from a server into a usable JavaScript object.
    - JSON.stringify()
        - Converting a JavaScript object into a string to send it across a network.
</details>

<details>
<summary><strong>JavaScript Function Expressions</strong></summary>

- **Function Expressions**
    - Creating a function inside an expression.
    - let sayHi = function() {  };
    - Semicolon required at the end because it is part of an assignment statement.
    - a function is a value that can be stored in a variable.
- **Callback Functions**
    - A function passed as an argument to another function.
    - Expected to be called back later to handle an action or event.
- **Declaration vs. Expression**
    - Declaration
        - Processed before code runs.
        - Can be called before it is defined.
        - Locked inside the block.
    - Expression
        - Runtime
        - Must be defined before it is called.
        - Can be assigned to a variable outside the block to escape it.
</details>

<details>
<summary><strong>JavaScript Function Expressions</strong></summary>

- **Array methods**
    - Add / Remove Items
        - push(...items) → Adds to end.
        - pop() → Removes from end.
        - shift() → Removes from beginning.
        - unshift(...items) → Adds to beginning.
        - arr.splice(start, deleteCount, ...items)
            - Can add, remove, and replace elements at any index.
        - arr.slice(start, end)
            - Creates a new subarray from start to end (not including end).
        - concat → Joins the array with other arrays or values.
    - Iterate
        - arr.forEach((item, index, array) => { ... })
            - Runs a function for every element.
    - Search
        - indexOf(item) → Returns index of first match (or -1 if not found).
        - includes(item) → Returns true / false (handles NaN correctly).
        - find(fn) → Returns the first element that matches the function condition.
        - findIndex(fn) → Returns the index of the first match.
        - filter(fn) → Returns an array of all elements that match the condition.
    - Transform
        - arr.map(item => newValue)
            - Calls a function on every element and returns a new array of results.
        - sort
            - Sorts the array in-place.
        - split / join
            - str.split(delim) → Turns String into Array.
            - arr.join(delim) → Turns Array into String.
        - arr.reduce((accumulator, item) => { ... }, initialValue)
            - Calculates a single value by iterating over the array.
    - Check Type
        - Array.isArray(value) → Returns true if the value is an array
</details>

### Video Notes
- **...**

</details>

<details>
<summary><strong>Week 3: Reactive App Specs</strong></summary>

### Class Notes
**Project Requirements (Due 3/1):**
- 3rd Party API Integration
- CSS Framework
- Data Storage
- React or Vue
- Deploy to Netlify

**Study Topics:**
- JavaScript Basics

</details>

<details>
<summary><strong>Week 2: React & JS Basics</strong></summary>

### Reading Notes
- **JavaScript:** `use strict`, variables, data types.
- **React:** Watched intro videos.

### Team Project
- Uploaded Bio & Profile Picture.

</details>

<details>
<summary><strong>Week 1: Logistics & Setup</strong></summary>

### Class Notes
- Syllabus review & team formation.
- **Assignments:** Finished `Hello-Explorer` (Refresher on MI349).
- **Setup:** Created Team GitHub Repo.

</details>