Hey, this is Dallen.
I created this app as a starting point to gather research about people's ability to multitask.  The current version will act as a control to test people's normal reading comprehension without any distraction.  Next, I will be doing a very similar app that has music playing in the background.

This is a simple looking app but it did help me learn a ton about React, JavaScript, JSX, HTML, React-Bootstrap, CSS and coding principles in general. Here are a few of the features I am most proud of in this project:
React Routing: I have used Routing before in a previous project but never as in depth as this.  I have a Breadcrumb navbar on the top of all pages that allows you to move throughout the app easily. There's a Begin button on the first page that takes you to the quiz when pressed. I have a Switch in the main App.js which catches all of the URL changes and puts up the page that matches.  This is really cool and took me a little while to wrap my head around but I got it working nicely.  I have a Redirect call on the last quiz question which automatically moves you to the results page.
Complex State handling: I don't know how complex it will look to a more experienced programmer but this too a lot of effort to figure out. I used React State Hooks throughout my project but the one I am most proud of is the state array declared in App.js that keeps track of the questions that the user gets wrong. I had a feeling that it was possible to store an array in state but I had never done it before.  I found many different tutorials online that were extremely helpful and eventually after many hours I figured it out.  This is how I am displaying the cards in the Quiz Results page that show the highlighted answers and whether they were correct or wrong.
Custom JSON Document: I got help from Professor Liddle with the basic formatting of my JSON document but I am proud of the fact that I was able to figure out how to pull data from this JSON document without any aid from Google or other people.  I feel very accomplished that I have a dynamic web page that can use any story and any set of questions that you put into the JSON file to quiz users on reading comprehension.

This project was a big learning experience for me.  Moving forward, I will have a much better understanding of state and props, react state hooks, React Boostrap components and how they can be useful, BrowserRouting from react-router, and overall a much higher confidence that I can make an app from scratch by myself.  It is a very fulfilling thing to look at a project you created and think back to when it was just a sketch on a piece of paper.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
