# PolymerTest

Sample Polymer webpage which functions as a simple task list. I built this in about 2 days to showcase a lot of the facets of Polymer as well as my skill involving responsive design.

The full webpage is hosted at emanguy.github.io/PolymerTest.

## Included files

 * index.html - The application entry point. Contains app layout elements and my custom elements which pass generate tasks and pass data.
 * elements/task-input.html - The custom element responsible for accepting user input and adding tasks. It has a property, "tasks" which is an array which it appends inputs to.
 * elements/task-grid.html - The custom element responsible for rendering the array of tasks passed to it from the task input. It has the ability to mutate the tasks array by removing tasks from it.
