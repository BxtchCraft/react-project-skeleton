## React Project Skeleton (Full Stack)
This is a React Skeleton Project that provides a basic structure for building full stack React applications.

### Installation Instructions

1. Clone the repository using the following command:
   ```
    git clone BxtchCraft/react-project-skeleton your-project
   ```
2. Install dependencies for the React client:
   ```
    cd your-project/client
    npm install
   ```
3. Install dependencies for the server side (Node.js):
   ```
    cd ../server
    npm install
   ```


### React Client Structure:
```
|-- /client (React)
    |-- src/
    |   |-- components/
    |   |   |-- App/ (not included)
    |   |   |   |-- index.js (not included)
    |   |   |   |-- App.js (not included)
    |   |   |   |-- App.test.js (not included)
    |   |   |
    |   |   |-- Button/ (not included)
    |   |   |   |-- index.js (not included)
    |   |   |   |-- Button.js (not included)
    |   |   |   |-- Button.test.js (not included)
    |   |   |   ...
    |   |
    |   |-- containers/
    |   |   |-- Home/
    |   |   |   |-- index.js
    |   |   |   |-- Home.js
    |   |   |   |-- Home.test.js
    |   |   |   ...
    |   |
    |   |-- services/
    |   |   |-- api.js (not included)
    |   |   |-- authService.js (not included)
    |   |   ...
    |   |
    |   |-- assets/
    |   |   |-- images/ (not included)
    |   |   |-- styles/ (not included)
    |   |
    |   |-- constants/
    |   |   |-- actionTypes.js (not included)
    |   |   |-- index.js (not included)
    |   |   ...
    |   |
    |   |-- actions/
    |   |   |-- userActions.js (not included)
    |   |   |-- index.js (not included)
    |   |   ...
    |   |
    |   |-- reducers/
    |   |   |-- userReducer.js (not included)
    |   |   |-- index.js (not included)
    |   |   ...
    |   |
    |   |-- utils/
    |   |   |-- utils.js (not included)
    |   |   |-- index.js (not included)
    |   |   ...
    |   |
    |   |-- index.js
    |   |-- App.css (not included)
    |   |-- setupTests.js (not included)
    |   |-- reportWebVitals.js (not included)
    |   |-- index.css (not included)
```

### Node.js Server Structure:
```
|-- /server (Node.js)
    |-- /src
    |   |-- /routes
    |   |-- /controllers
    |   |-- /models
    |   |-- /services
    |   |-- index.js
    |-- package.json
```

The React client structure contains directories such as `components`, `containers`, `services`, `assets`, `constants`, `actions`, `reducers`, and `utils`. These directories are organized to provide a modular and scalable architecture for your React application. Each component or container has its own directory with relevant files, including JavaScript files for logic, test files, and an `index.js` file for exporting.

The `services` directory contains files for interacting with APIs and handling authentication. The `assets` directory is used for storing images and styles. The `constants` directory holds files for defining action types and other constants. The `actions` and `reducers` directories are responsible for managing state using Redux.

The `utils` directory contains utility functions that can be used throughout the application. The root directory includes the main `index.js` file for rendering the React app, along with additional configuration files such as `App.css`, `setupTests.js`, and `reportWebVitals.js`.

On the server side, there is a separate `server` directory which includes a Node.js server implementation. Inside the `src` directory, you will find directories for `routes`, `controllers`, `models`, and `services`, along with an `index.js` file for starting the server. The `package.json` file manages the server-side dependencies.

Feel free to customize and expand upon this React Skeleton Project to suit your specific requirements.
