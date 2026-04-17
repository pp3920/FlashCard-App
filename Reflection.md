Where AI saved time.
AI saved time by quickly generating the initial HTML structure, CSS grid layout, and JavaScript boilerplate for modal handling and deck management. Instead of manually setting up layouts and writing repetitive DOM manipulation code, I could focus more on understanding logic and integration. It also helped speed up UI structuring and accessibility patterns (like focus management in modals).

At least one AI bug you identified and how you fixed it.
One issue from AI-generated code was the use of duplicate id values for multiple elements (for example, multiple <p id="questions">). Since IDs must be unique, this could break DOM selection and future JavaScript logic. I fixed it by replacing duplicate IDs with class-based selectors and ensuring dynamic content areas are properly structured. 

A code snippet you refactored for clarity.
I added an accessible modal system with:

Focus trapping inside the modal
ESC key support to close modal
Returning focus to the button that opened the modal

One accessibility improvement you added.


What prompt changes improved AI output.
The biggest improvement came from making prompts more specific and constraint-based, for example:

Instead of: “create a modal”
“Create an accessible modal with focus trap, ESC to close, and return focus to opener in vanilla JS”
Instead of vague UI requests:
 I specified “plain JS, no libraries, include accessibility requirements”
Adding structure requests like:
 “step-by-step, include HTML + CSS + JS separately”

This reduced unnecessary code, improved correctness, and made the output easier to integrate into my project.