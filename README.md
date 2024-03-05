<h1 align="center">React JS- A Documentation on React JS</h1>

![React Logo](https://mariosfakiolas.com/uploads/react.jpeg)

# Table of Contents
[What is React?](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#what-is-react-)

[Why React?](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#why-react-)

[React JS Advantages](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#reactjs-advantages)

[Virtual Document Object Model (DOM)](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#virtual-document-object-model-dom)

[Installation](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#installation)

[React Router](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#react-router) 

[Hooks](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#hooks)

[Components](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#components)

[React APIs](https://github.com/amancoder17/React_Documentation?tab=readme-ov-file#react-apis)

# What is React ?

React is a framework that employs Webpack to automatically compile React, JSX, and ES6 code while handling CSS file prefixes. React is a JavaScript-based UI development library. Although React is a library rather than a language, it is widely used in web development. The library first appeared in May 2013 and is now one of the most commonly used frontend libraries for web development.

React offers various extensions for entire application architectural support, such as Flux and React Native, beyond mere UI.

# Why React ?
React’s popularity today has eclipsed that of all other front-end development frameworks. Here is why:

- Easy creation of dynamic applications: React makes it easier to create dynamic web applications because it requires less coding and offers more functionality, as opposed to JavaScript, where coding often gets complex very quickly.
- Improved performance: React uses Virtual DOM, thereby creating web applications faster. Virtual DOM compares the components’ previous states and updates only the items in the Real DOM that were changed, instead of updating all of the components again, as conventional web applications do.
- Reusable components: Components are the building blocks of any React application, and a single app usually consists of multiple components. These components have their logic and controls, and they can be reused throughout the application, which in turn dramatically reduces the application’s development time.
- Unidirectional data flow: React follows a unidirectional data flow. This means that when designing a React app, developers often nest child components within parent components. Since the data flows in a single direction, it becomes easier to debug errors and know where a problem occurs in an application at the moment in question.
- Small learning curve: React is easy to learn, as it mostly combines basic HTML and JavaScript concepts with some beneficial additions. Still, as is the case with other tools and frameworks, you have to spend some time to get a proper understanding of React’s library.
- It can be used for the development of both web and mobile apps: We already know that React is used for the development of web applications, but that’s not all it can do. There is a framework called React Native, derived from React itself, that is hugely popular and is used for creating beautiful mobile applications. So, in reality, React can be used for making both web and mobile applications.
- Dedicated tools for easy debugging: Facebook has released a Chrome extension that can be used to debug React applications. This makes the process of debugging React web applications faster and easier.

# ReactJS Advantages
<p align="center">
  <img src="https://media.licdn.com/dms/image/D4D12AQHOSye8D0thTA/article-cover_image-shrink_600_2000/0/1702363019916?e=2147483647&v=beta&t=vP_biLMP_u95MaIJklghBa3Kipa98AGo35LwR3iuijQ">
</p>

- React.js builds a customized virtual DOM. Because the JavaScript virtual DOM is quicker than the conventional DOM, this will enhance the performance of apps. 
- ReactJS makes an amazing UI possible. 
- Search - engine friendly ReactJS. 
- Modules and valid data make larger apps easier to manage by increasing readability. 
- React integrates various architectures. 
- React makes the entire scripting environment process simpler. 
- It makes advanced maintenance easier and boosts output. 
- Guarantees quicker rendering 
- The availability of a script for developing mobile apps is the best feature of React.
- ReactJS is supported by a large community.

# Virtual Document Object Model (DOM) 
<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*OY-um1C1N9evOIlYjzADZg.png">
</p>

The Virtual DOM is React's lightweight version of the Real DOM. Real DOM manipulation is substantially slower than virtual DOM manipulation. When an object's state changes, Virtual DOM updates only that object in the real DOM rather than all of them.
- What is the Document Object Model (DOM) ?

DOM (Document Object Model) treats an XML or HTML document as a tree structure in which each node is an object representing a part of the document.
<p align="center">
  <img src="https://www.w3schools.com/js/pic_htmltree.gif">
</p>

- How do Virtual DOM and React DOM interact with each other?

When the state of an object changes in a React application, VDOM gets updated. It then compares its previous state and then updates only those objects in the real DOM instead of updating all of the objects. This makes things move fast, especially when compared to other front-end technologies that have to update each object even if only a single object changes in the web application.

# Installation

### Step 1: Install Node.js and npm

 Before installing React, you need to have Node.js and npm (Node Package Manager) installed on your system. If you haven’t already installed them, follow these steps:

- Visit the Node.js download page at: https://nodejs.org/en/download/
- Download the installer for your Windows system (either the LTS or Current version is fine, but the LTS version is recommended for most users)
- To install Node.js and npm, please run the installer and carefully follow the provided prompts.
<p align="center">
  <img src="https://kinsta.com/wp-content/uploads/2023/04/nodejs-download.png">
</p>

After the installation is complete, you can verify that Node.js and npm are installed by opening a command prompt and running the following commands:
                       
    node -v npm -v

### Step 2: Install and Create a New React Project

Create React App is a command-line tool that simplifies the process of setting up a new React project with a recommended project structure and configuration. To install Create React App globally, open a terminal in any environment and run the following command:

    npm init -y
    npx create-react-app my-app

Replace “my-app” with the desired name for your project. Create React App will create a new directory with the specified name and generate a new React project with a recommended project structure and configuration.

### Step 3: Go To the Project Directory and Start the Development Server

Once the project is created, head over to the project directory by running the following command in the command prompt:
       
    cd my-app
Now, start the development server by running the following command:

    npm start

### Output

    aman@aman-Mi-NoteBook-14:~/reac doc$ npm init -y
    Wrote to /home/aman/react doc/package.json:

    {
    "name": "react-doc",
    "version": "1.0.0",
    "description": "",
    "main": "index.js",
    "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
    },
    "keywords": [],
    "author": "",
    "license": "ISC"
    }

    aman@aman-Mi-NoteBook-14:~/reac doc$ npx create-react-app my-app

    Creating a new React app in /home/aman/reac doc/my-app.

    Installing packages. This might take a couple of minutes.
    Installing react, react-dom, and react-scripts with cra-template...


    added 1490 packages in 1m

    254 packages are looking for funding
    run `npm fund` for details

    Initialized a git repository.

    Installing template dependencies using npm...

    added 69 packages, and changed 1 package in 7s

    258 packages are looking for funding
    run `npm fund` for details
    Removing template package using npm...


    removed 1 package, and audited 1559 packages in 3s

    258 packages are looking for funding
    run `npm fund` for details

    8 vulnerabilities (2 moderate, 6 high)

    To address all issues (including breaking changes), run:
    npm audit fix --force

    Run `npm audit` for details.

    Created git commit.

    Success! Created my-app at /home/aman/reac doc/my-app
    Inside that directory, you can run several commands:

    npm start
    Starts the development server.

    npm run build
    Bundles the app into static files for production.

    npm test
    Starts the test runner.

    npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

    We suggest that you begin by typing:

    cd my-app
    npm start

    Happy hacking!
    
    aman@aman-Mi-NoteBook-14:~/reac doc$ cd my-app
    aman@aman-Mi-NoteBook-14:~/reac doc/my-app$ npm start
    Compiled successfully!

    You can now view my-app in the browser.

    Local:            http://localhost:3000
    On Your Network:  http://192.168.89.119:3000

    Note that the development build is not optimized.
    To create a production build, use npm run build.

    webpack compiled successfully


<p align="center">
  <img src="https://kinsta.com/wp-content/uploads/2023/04/react-on-windows.png">
</p>


# React Router

React Router enables "client side routing".

In traditional websites, the browser requests a document from a web server, downloads and evaluates CSS and JavaScript assets, and renders the HTML sent from the server. When the user clicks a link, it starts the process all over again for a new page.

Client side routing allows your app to update the URL from a link click without making another request for another document from the server. Instead, your app can immediately render some new UI and make data requests with fetch to update the page with new information.

This enables faster user experiences because the browser doesn't need to request an entirely new document or re-evaluate CSS and JavaScript assets for the next page. It also enables more dynamic user experiences with things like animation.

Client side routing is enabled by creating a Router and linking/submitting to pages with Link and <Form>:


    import * as React from "react";
    import { createRoot } from "react-dom/client";
    import {
    createBrowserRouter,
    RouterProvider,
    Route,
    Link,
    } from "react-router-dom";

    const router = createBrowserRouter([
    {
    path: "/",
    element: (
      <div>
        <h1>Hello World</h1>
        <Link to="about">About Us</Link>
      </div>
    ),
    },
    {
    path: "about",
    element: <div>About</div>,
    },  
    ]);

    createRoot(document.getElementById("root")).render(
    <RouterProvider router={router} />
    );

# Hooks
Hooks let you use different React features from your components. You can either use the built-in Hooks or combine them to build your own. This page lists all built-in Hooks in React.

### Built-in React Hooks
#### State Hooks

State lets a component “remember” information like user input. For example, a form component can use state to store the input value, while an image gallery component can use state to store the selected image index.

To add state to a component, use one of these Hooks:

1) useState declares a state variable that you can update directly.
2) useReducer declares a state variable with the update logic inside a reducer function.

#### Context Hooks

Context lets a component receive information from distant parents without passing it as props. For example, your app’s top-level component can pass the current UI theme to all components below, no matter how deep.

useContext reads and subscribes to a context.

### Effect Hooks 

Effects let a component connect to and synchronize with external systems. This includes dealing with network, browser DOM, animations, widgets written using a different UI library, and other non-React code.

useEffect connects a component to an external system.

    function ChatRoom({ roomId }) {
    useEffect(() => {
    const connection = createConnection(roomId);
    connection.connect();
    return () => connection.disconnect();
    }, [roomId]);

Effects are an “escape hatch” from the React paradigm. Don’t use Effects to orchestrate the data flow of your application. If you’re not interacting with an external system, you might not need an Effect.

There are two rarely used variations of useEffect with differences in timing:

  1) useLayoutEffect fires before the browser repaints the screen. You can measure layout here.
  2) useInsertionEffect fires before React makes changes to the DOM. Libraries can insert dynamic CSS here.

# Components
React exposes a few built-in components that you can use in your JSX.
 ## Built-in components
 
    - <Fragment> alternatively written as <>...</>, lets you group multiple JSX nodes together.
    - <Profiler> lets you measure rendering performance of a React tree programmatically.
    - <Suspense> lets you display a fallback while the child components are loading.
    - <StrictMode> enables extra development-only checks that help you find bugs early.
    
You can also define your own components as JavaScript functions.

# React APIs
The react package exports a few other APIs that are useful for defining components. This page lists all the remaining modern React APIs

        
   - createContext lets you define and provide context to the child components. Used with useContext.
   - forwardRef lets your component expose a DOM node as a ref to the parent. Used with useRef.
   - lazy lets you defer loading a component’s code until it’s rendered for the first time.
   - memo lets your component skip re-renders with same props. Used with useMemo and useCallback.
   - startTransition lets you mark a state update as non-urgent. Similar to useTransition.



 
    
    
