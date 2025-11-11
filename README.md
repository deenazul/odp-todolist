# odp-todolist
## requirements
1. title, description, dueDate, priority. notes, checklist.
2. projects or separate lists of todos.
3. open app ada default project
4. create new, choose project todos go into
5. create new todos, status, priority etc from dom-related stuff.
6. View all projects.
7. View all todos in each project (probably just the title and duedate… perhaps changing color for different priorities).
8. Expand a single todo to see/edit its details.
9. Delete a todo.
10. localstorage/web storage api

Set up a function that saves the projects (and todos) to localStorage every time a new project (or todo) is created, and another function that looks for that data in localStorage when your app is first loaded. Additionally, here are a couple of quick tips to help you not get tripped up:

Make sure your app doesn’t crash if the data you may want to retrieve from localStorage isn’t there!
You can inspect data you saved in localStorage using DevTools! To do this, open the Application tab in DevTools and click on the Local Storage tab under Storage. Every time you add, update and delete data from localStorage in your app, those changes will be reflected in DevTools.
localStorage uses JSON to send and store data, and when you retrieve the data, it will also be in JSON format. Keep in mind you cannot store functions in JSON, so you’ll have to figure out how to add methods back to your object properties once you fetch them.