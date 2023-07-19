# Todolist-with-node-persist
Module Assignment2: To Do List App
This assignment contains ToDo List app in this app we can create the todo list. This app divided into two parts that is frontend and backend.
Frontend: I have used react to implement this app. I have deleted some excessive folder that are not needed. And created some folder like pages. To install this app, I have given command npx create-react-app
App.js : in this file I have imported react, React-router-dom and todo page. Then I gave routes to the Todo page with help of route.
 I have used some styling effect to the app I have created file todo.css to style the app and created file todo.js where I have imported react and todo.css.   
Todo.js: In react component we have to use props to pass data from parent component to child so here I have used defalutEntry to pass totos data. Here I have created function ToDoApp() where I have declared const host and gave the path where the server will start.
I have use UseState to store and manage data within component and react automatically re-renders the components. I have used the handlesubmit that basically handles the event form element that handles submission in react. E.preventDefault() method is use to prevent default action associates with that event that is todoname. I have use jsx in this file to add some Html  form elements like input group and buttons. 
Index.js: In this page I have imported react, react-dom and app. Js and create root with getElementBy root.render. the app.js component wrapped with the react.strictMode.

Backend: In this folder I have created server.js to store local storage with the help of node-persist, I have given server port 4000.
I have used post method to post all todos to the database with URL app.post”/addTodo”
 To get all todos which is added through Post with URL localhost:4000/getTodo.
I have used the app.delete method to delete all todos when the page get refreshed.
I have deleted some packges before submitting this assignment because of storage issues while uploading to run this program we have to install packages that are required to run this app.
