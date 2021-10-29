# React Vocabulary

Write the best definitions you can of the following terms. Do this from memory; the goal isn't just to have the list, but to have it reflect your current understanding. It's OK for your definitions to be inaccurate or incomplete, you'll be updating them as you learn.

## Core React/SPA Terms

| Term | Definition |
| --- | --- |
| Application State | State that is held by the application itself, not any particular component |
| Bound State | State that is bound to a JSX element or other part of the component |
| Child Component | Component that is hierarchically descended of another component. Also component passed as argument toanother component. |
| Component Hierarchy | A tree structure showing the component's organization structure relative to the app. |
| Component Rerender | When the virtual DOM regenerates new DOM nodes. |
| Component | Basic unit of React. It encapsulates state, properties, and UI. Implmented as a function that returns JSX elements. Can be reusable. |
| Computed Value | Evaluated value based on conditions. Can be pulled from props or other logic. Typically derived from state. |
| Conditional Rendering | Displays JSX elements based on a condition. The condition needs to be an expression. |
| Context Provider | Wrapper around a part of the hierarchy that allows them to access application state. |
| Context | Tools for tunneling state from one part of the app to another. |
| Create React App | Package from npm that builds a skeletal React application. |
| Dumb Component | Component that does not manage its own state. |
| Dynamic Segment | Parse the data out of route paths, prefixed with a colon. |
| React Event Handler | Responds to synthetic events. How event listeners are handled in React. |
| Hook | Allows React class functionality in a functional component. Hooks into component lifecycle. |
| JSX Element | Element created using JSX, allowing declarative bound state and event management in a syntax similar to HTML. |
| JSX | JavaScript extensions that allows you to write HTML elements in a React app. |
| Keys | Used in lists to allow JSX to render items consistently. Must be unique within a list. Cannot use array indexes or other dynamic values. |
| Library | Collection of pre-written code that can be reused for programming. |
| Nested Route | Component that came from a `<Switch>` inside of a `<Switch>`. |
| One-Way Data Flow | Data passed down from a parent component to children. Components should never read or modify another component's data directly. Data can be primitive values, functions, objects, or other JSX elements. Functions being passed down can modify state in other components. |
| Parent Component | A component in the hierarchy that has a child or children. |
| React Router | Library used in React that encapsulates navigation logic. Uses declarative logic. |
| React State | Data that changes over time in a React component. |
| React | Component-based front-end UI library. |
| Render | Modifying the DOM. |
| Route | Definition of each page within a router. |
| React Router | Third party library for incorporating SPA routing. |
| SPA Routing | Rendering specific components based on the URL. |
| SPA | Single-page application. Uses async HTTP requests for data instead of request new documents. |
| Side-Effect | Anything that occurs outside a scope after being triggered inside that scope. |
| State Management | Managing application state, often with third-party tools. |
| Top-level Component | Entrypoint into a React app. |
| Transpilation | Transforms code without changing the level of abstraction. Used in React to transforms JSX code into HTML, CSS, and JS so the browser can understand it. |
| View | Represents a virtual "page". Module section that gets swapped out and interchanged. Displays a certain set of information. |
| Virtual DOM | Virtual representation of the UI, kept in memory, and syncs with the real DOM when changes happen. |
| Webpack | Build tool. Handles bundling, transpilation, and data transformation, assets and dependencies. |
| `useContext` | React hook for creating an application state container. |
| `useEffect` | Handle any UI changes or side-effects. Takes two arguments, a function and an array of dependencies. |
| `useParams` | Gives you your dynamic segment parameters. |
| `useRouteMatch` | Get the URL, path, and params from the route, used to build relative paths. |
| `useState` | Hook that declares stateful variables, gives you a function for updating the state. |

## Supporting Ideas

| Term | Definition |
| --- | --- |
| API | |
| API Data | |
| API Server | |
| Alias | |
| Argument | |
| Array Index | |
| Boolean | |
| CSS | |
| Conditional Logic | |
| DOM | |
| DOM Element | |
| DOM Event | |
| DOM Event Handler | |
| DOM Node | |
| Data Type | |
| Database-generated ID | |
| Dependency | |
| Deployment | |
| Event Listener | |
| Expression | |
| Falsy | |
| Favicon | |
| Function Parameter | |
| HTML | |
| HTML Document | |
| HTML Template | |
| HTTP Request | |
| HTTP Response | |
| Hoisting | |
| Initialization | |
| Iteration | |
| JSON | |
| JavaScript | |
| JavaScript: Arrow Function | |
| JavaScript: Destructuring | |
| JavaScript: Spreading | |
| JavaScript: Template Literal | |
| JavaScript: `.map` | |
| JavaScript: `export` | |
| JavaScript: `fetch` | |
| JavaScript: `if`/`else` | |
| JavaScript: `import` | |
| JavaScript: `localStorage` | |
| Lag | |
| Model | |
| Module | |
| Namespacing | |
| Node Package | |
| Package | |
| Package Manager | |
| Path | |
| Port | |
| Programmatic | |
| Resource | |
| Server | |
| Shallow Copy | |
| Static Website | |
| Static File | |
| Static Value | |
| Stylesheet | |
| Syntax | |
| Ternary Expression | |
| Truthy | |
| UI Badge | |
| URL | |
| Web Page | |
| Website | |
| `.gitignore` | |
| `node_modules` | |
| `package.json` | |
| localhost | |
| npm | |
| npx | |
