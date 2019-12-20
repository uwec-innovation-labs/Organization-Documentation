# The React Learning Guide

This guide is only a recommendation of how to learn React. There are many ways to learn it. React is library created by Facebook which allows us to build components for the frontend. Its much more scalable and easier to maintain.

## Step 1: Learn JavaScript

You could definitly start by learning React, but you will likely struggle without a working knowledge of JavaScript. Understanding some of the syntax will go a long way in the learning process. Also, have knowledge of HTML and CSS as well, as they will also play a role within React.

Resources:

- Introduction to JavaScript (Codeacademy): https://www.codecademy.com/learn/introduction-to-javascript
- Learn JavaScript in 1 Hour (Youtube): https://www.youtube.com/watch?v=W6NZfCO5SIk

## Step 2: Learn React

Now you are ready to learn about React, a powerful web framework used for the frontend. I recommend reading through the documentation, getting it installed on your computer, and playing around with it as you watch videos about it.

Resources:

- React Installation (React): https://create-react-app.dev/docs/getting-started/
- React Documentation (React): https://reactjs.org/docs/hello-world.html
- Learn React (Youtube): https://www.youtube.com/watch?v=Ke90Tje7VS0

## Step 3: Other Important Packages

With NPM, which is what you used to install react, you can actually install packages which makes certain things really easy. Here is a recommendation of a few you might use in the frontend. I will break them up by category. Note: A lot of these packages will have a site associated with them with documentation on how to use them.

When a package is installed its dependencies and itself are put in the node_modules folder.

### Design Frameworks

- Bootstrap: https://www.npmjs.com/package/bootstrap
- Material-UI: https://www.npmjs.com/package/@material-ui/core
- Reactstrap: https://www.npmjs.com/package/reactstrap

### Graphing

- Chart.js: https://www.npmjs.com/package/chartjs
- D3.js: https://www.npmjs.com/package/d3

### Requests

- Axios: https://www.npmjs.com/package/axios
- GraphQL: https://www.npmjs.com/package/graphql

### Cookies and LocalStorage

- Cookie: https://www.npmjs.com/package/cookie

### Sockets

- Socket.io: https://www.npmjs.com/package/socket.io

### Desktop Builds

- Electron: https://www.npmjs.com/package/electron

### Mobile Builds

- React Native: https://www.npmjs.com/package/react-native

## Step 4: TypeScript and Continued Learning

The final recommended thing to look into is TypeScript. TypeScript basically makes JavaScript strongly typed and more Object-Oriented. Its tricky, but worth learning eventually. Other than that, there are so many more things to learn and to continue to learn as new things come out. Be curious and try out new things from time to time.

# Standards
There is some simple things you can do in order to make a project more managable and easier to understand. With that, we have a few things to keep in mind when starting up a React project.

## Setting up a React Project
In order to initialize the boilerplate code for React, run the command 'npx create-react-app somefoldername'. Here are some additional things to setup for most projects.
- Create a componenets folder within the src folder. This is where you will organize the React components you build.
- Remove the serviceWorker.js found in the src folder.
- In the index.js in the src folder, remove the serviceworker line found on line 12 usually and the comments associated with it
- Remove the line 'import * as serviceWorker from './serviceWorker';' in the index.js file as well.
- Remove the logo.svg found in the src folder
- Remove 'import logo from './logo.svg';' and everything between the <div> </div> tags. This will cleanup the base code
- Remove the README.md file in the root. We can re-add this later if we need it.
- I would also change the title of the app found in the public folder in the index.html file.
