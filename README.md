<div id="top"></div>

# Simple React To-Do List ✅

## About the App:
A simple To-Do list made with React.JS.

The To-Do list has simple features such as
Adding, Removing, Editing, Crossing Off user defined items.

## Demo Link: 🔗
Accessible at my Website: <a href="https://arielj.ca/todo" target="_blank">arielj.ca/todo</a>

## Screenshots:📷
#### Adding To-Do List 📝

<img src="/screenshots/add.gif" width="750"/>

#### Removing To-Do List 🗑️

<img src="/screenshots/remove.gif" width="750"/>

#### Editing To-Do List ✍️

<img src="/screenshots/edit.gif" width="750"/>

<p align="right">(<a href="#top">back to top</a>)</p>

## Technologies Used: ⚙️
This Application was Created with
- [React.js](https://reactjs.org/)
- [JavaScript](https://www.javascript.com/)
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
- HTML

<p align="right">(<a href="#top">back to top</a>)</p>

## Setup / Installation: 💻
### Prerequisites
- npm
  ```npm install -g npm```
### Instalation
1. Download / Clone the repo
2. Use the command ```npm install``` to run the app
3. Run the app with the command ```npm start```

<p align="right">(<a href="#top">back to top</a>)</p>

## Approach: 🚶

As React.JS is a powerful front-end JavaScript library, the design for the To-Do List application utilizes React's Functional Components and Hooks (mainly Effect Hooks ```useEffect```, ```useState``` and ```useRef```).

Sectioned out into 3 separate JavaScript files where each script handles certain aspects of the To-Do List.

#### ```Todo.js```
 
 The _**Todo.js**_ handles the mapping of the To-Do List. Furthermore, it parses the data into 2 variables, a todo _String_ (which stores the todo item) and the index of the todo _String_. The submission of new values is also handled by _**Todo.js**_ as it utilizes React's useState hook and the associated index value of a todo _String_ to modify and change it's _String_ value.

#### ```TodoForm.js```

The _**TodoForm.js**_ handles the generation of a new To-Do item. It generates an ID for each submission and utilizes React Hooks (_useState_, _useEffect_ and _useRef_) to handle submission and all user applied changes onto the form (textbox) of the To-Do List application.

#### ```TodoList.js```
   
The _**TodoList.js**_ handles the appending of the To-Do element to the To-Do array. Furthermore, it handles the update process and removal of a To-Do entry. It utilizes the index to find and determine which To-Do entry the user specifies to modify.

<p align="right">(<a href="#top">back to top</a>)</p>

## Status: 📶
- [x] Ability to Delete Entries
- [x] Ability to Modify Entries
- [x] Animate Background
- [ ] Ability to Sort Alphabetically

██████████████]99% Completion

See the [open issues](https://github.com/ArielJ3/react-todo/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Ariel Johannes - me@arielj.ca

Project Link: [https://github.com/ArielJ3/react-todo](https://github.com/ArielJ3/react-todo)

<p align="right">(<a href="#top">back to top</a>)</p>
