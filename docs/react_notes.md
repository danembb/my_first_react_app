# React Notes
## Terminology

`className`: jsx convention for declaring a class, as opposed to HTML's `class`.
`Component`: A piece of code that returns or renders jsx.
`Props`: Props (or Properties) are arguments that you pass into react components. They are passed via attributes. They allow you to pass dynamic data through react components.
`Functional Component`: A jsx variable that can be imbued with real javascript logic. Similar to Rails magic. 
`React fragment`: Similar to an empty div. An expression denoted by left/right arrow (`<>` `</>`)
    - If you want to render 2 different elements, one next to another, they must be wrapped in a react fragment.
`Events`: When a user interacts with the DOM. Could be a mouse-click or button click.
`Hooks`: Basic hooks: `useState` `useEffect` `useContext` (Check out React documentation)
## Concepts

#### Creating An App:
To create your first react app: 
    - download `node.js` from the nodejs.org website
    - use the command `npx create-react-app (app name)` or create a folder in a directory on your computer and drag it into your VScode     editor, then use the command `npx create-react-app` with the current directory

To start your app, use the command: `npm start`. You can have this open while editing app to see real-time updates.

#### File/Folder Structure
Main
    - `/node_modules/`: Where the code for all the packages lives
    - `/public/`: where the `/index.html` file exists. This is where code is injected.
    - `/src/`: All logic goes here. Everything related to app is in the `src` folder. 
        - `/index.js`: The starting point of every React.js application. In here, `ReactDOM` is called **once**, no matter how big the application grows. The DOM is used to render the components and application into the `<div>` with an ID of `'root'`. This is then injected into `/public/index.html/`.
    - `package.json`: Where the dependencies/packages the app has installed live. 


## Conventions

- Functional components are primarily used now-days. No more 'class-based madness'. 

JSX
- You can dynamically render real data (injecting js logic) directly into a `.js` file through using curly braces (`{}`). 