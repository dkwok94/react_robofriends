This project is a simple app that is built using React and two APIs: [Robohash](https://robohash.org/) and [JSONPlaceholder](https://jsonplaceholder.typicode.com/).

The project consists of a main App container as a parent and CardList and SearchBox components as children which receive the particular state features from the App container in their props. 

When the application is first loaded, it contacts the JSONPlaceholder API which sends back a list of random people and sets the state with this list of people. It then renders the SearchBox and CardList components and passes various parts of its state to these components. The SearchBox component gets passed an empty searchField property which detects changes when a user types. The CardList component gets passed the user list from the state so that it can create Card components for each user and render those. 

<img src="https://drive.google.com/open?id=1uovvbl_-t-hSup4H89C8e1aZT4BM07PD" />

Thus the user will see a bunch of cards on the screen and when they type anything into the search box, the cards displayed will update according to what is typed due to a filtering function embedded into the App which automatically changes the user list of the state.

<img src="https://drive.google.com/open?id=1gIOvCW-N4PwbDbgCmDQWxhsS5gc0Bsf2" />

---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
# react_robofriends
