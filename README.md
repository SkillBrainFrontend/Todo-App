# Todo App

Learn React by implementing a Todo App alongside your Frontend mentor as a part of **React** course from [SkillBrain©](https://skillbrain.com/)

Building a Todo App is easy and does not take much time but it teaches you some important concepts which are very important to understand for any developer.

**Check the docs below before procedeeng to your task.** 
👉🏻 [Git Helper, Project Setup and Rules](./GIT_HOW_TO.md)

___


### Prerequisites

Since these are your first weeks with the React world, we would keep things simple. The starting code already includes the core components and styles - the building blocks you will need to implement this task. 

- First, open the `App.js` file and find `App` Component - the main component in React which acts as a container for all other components. 
- Next, you should identify the main components and how these components are displayed, how you can interact with these components, and how you can pass some data to them.
- Make sure you understand the role of these components as you are going to use them in your implementation.


```zsh
.
├── node_modules
├── README.md
├── public
├── package-lock.json
├── package.json
└── src
    ├── reportWebVitals.js
    ├── App.css
    ├── index.js
    ├── index.css
    ├── components // 👈🏻 here are the core components.
    │   ├── card
    │   ├── todo-item
    │   ├── input
    │   ├── checkbox
    │   ├── button
    │   ├── add-todo
    │   └── modal
    └── App.jsx // 👈🏻 here is the starting point.

```

___

## Requirements
 
>In software development, a user story is an actionable goal from the perspective of the user. Defining user stories before you begin your work will help you focus on work.
 
#### The app should fulfill the following stories:

- view all todos in two separated list
  - active todos 
  - completed todos.
- add a task
- mark any task as completed
- delete any task
- edit any task




##### Acceptance criteria

1. View all todos in two separated list **active todos** and  **completed todos** ⭐️
    - Store your todos in a `state`. Initialize it from `TODOS_MOCK` array, found in `App.js` file. This array will help you to understand how you should organize your data.
    - Diplay todos with `<TodoItem />` component. **HINT!** (use array methods: `map` and `filter`)
      * The only `prop` it accepts - `completed` is responsible for styling the completed / active items. You don't have to worry about styling. Just make sure you pass the proper values.
      * Initially, the  `<TodoItem />` components displays some static data. 
      *  Next, make it receive data from outside through `props`.
  
    
  
