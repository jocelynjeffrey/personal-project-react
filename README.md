# Bridge Personal Project

## Requirements

- Create a login page: a user landing on the page should be able to input a username and submit it.

- Once the user has logged in, they should be able to see the most recent repositories (repos) that use has forked and their most recent pull requests.

- Each of the forked repos should display the name of that repo as a link, and link to the base repo.

- Each of the pull requests should display the title of the pull request as a link, and link to that pull request.

- Each of the pull requests should have, in addition, a visual indicator for whether it is open, closed or merged. This could be colour coded, or just have the status in words next to it.

## Data Source
Your data source is the Github API! You'll be using the events and pull-request endpoints. Using the Github API display:
- the most recent repositories a given user has forked
- the most recent pull requests a user has created

The events endpoint will return all the most recent events (or actions) a user has completed. Everything from opening a pull request to forking a repo to starring a repo. All the different types of events are clarified by a type property. E.g. ForkEvent and PullRequestEvent which you can use to get the info you need. The pull request endpoint will give you the information you need to find out the status of a given pull request (whether its open, closed or merged)

**EXAMPLES**
https://api.github.com/users/pkanal/events
https://api.github.com/repos/bridge-school/bridgeschool.io/pulls/39

Go to those URLs in your browser to have a look at the JSON response. Its a good idea to copy these as example responses into a file in case you hit the rate limit of the API and that way you can keep on developing.

To view these responses in a nice format, install a chrome extension that helps you view JSON, e.g. https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en

## Technical requirements
React and Redux, of course! You should use create-react-app, a convenient way to bootstrap React apps. You'll also want to install dev-tools browser extensions for React and Redux.

You can refer to the finished version of a similar Github app here to get started: https://github.com/melaniebrgr/github-app-with-redux-after/tree/final-20180927-1304.

## Instructions

1. Fork this repository to your own github
2. Clone the forked version of this repository to your computer
3. Set up create react app and make an initial commit to the master branch of your repo

**Part One**
Complete the requirements outlined above using only React (no Redux) and push it up to the master branch of your repo

**Part Two**
Create a new branch called `redux-solution` and port your React only solution to use Redux. Only complete part two after you have finished part one.

**Submissions**
Once you have completed your personal project we'll provide a Google form for you to submit the link to your repo.

If you have any questions, please reach out on slack on the #help-me or #dev-cohort-6 channel! Happy hacking!


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
