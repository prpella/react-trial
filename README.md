## 📝 Instructions

Deal with organizational structure. Some companies have a flat hierarchy, but most companies have a traditional reporting hierarchy with multiple levels. A common task for administrators is to select a subset of the organization. For example one or a couple of teams and some users from anywhere in the organization. They might want to do a selection such as:

![User picker example](public/mockup.png)

### Basic tasks (user stories)

- As a user I want to see the organization’s hierarchical structure.
- As a user I want to select individual employees.
- As a user I want to save the selection. (That means the data gets serialized, e.g. as JSON, and sent to a server, stored in a file or – for simplicity – logged on the console).

### Bonus tasks (user stories)

- As a user I want to select entire teams without having to select every employee individually.
- Optimize the code for a potentially very large number of users. You should be able to reason about data structures, memory requirements and runtime complexity

### What we'd like to see

- You need to use JavaScript and React for this task. This project is compiled using Typescript, and you're very welcome to use it.
- Do not make assumptions about the number of levels in the hierarchy

The primary goal is to solve the basic tasks, not to demonstrate your knowledge of libraries, frameworks or programming techniques.
If additional libraries help you, use them, but don't waste time on setting them up or refactoring things.

### Additional remarks

- The user interface does not need to be pixel-perfect. This task is mainly about coding in JavaScript and not so much about CSS styling or visual design.
- You can choose how to handle the view state (i.e. the current selection and manipulation of it). We are interested to hear the reasoning behind your choice though.
- Whether or not you want to write tests is up to you here.
- You can commit directly to this repository and also push, so you don’t have to fork.

## 🚀 Get started

Please follow the instructions below to get started. We already included the necessary test data in a JSON file. Your starting point is [`src/App.js`](src/App.js).

### Requirements

- NodeJS v10.1
- npm v6.2


