1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?


Ans:
    getElementById selects one element by its id.
    getElementsByClassName selects multiple elements with the same class name.
    querySelector selects the first matching element using a CSS selector.
    querySelectorAll selects all matching elements using a CSS selector.

2. How do you create and insert a new element into the DOM?

Ans:
    we can create a new element using document.createElement().
    Then add content or attributes to it.
    Finally, use appendChild() or append() to insert it into a parent element.

 event from moving to parent elements.

 3. What is Event Bubbling? And how does it work?

Ans:
    Event Bubbling is when an event starts from the target element and moves upward to its parent elements.
    For example, if we click a button inside a div, the button event runs first, then the div event runs.

4. What is Event Delegation in JavaScript? Why is it useful?

Ans:
    Event Delegation means adding an event listener to a parent element instead of  multiple child elements.
    It is useful because it improves performance and works for dynamically added elements.

5. What is the difference between preventDefault() and stopPropagation() methods?

Ans:    
    preventDefault() stops the browser’s default action.
    stopPropagation() stops the