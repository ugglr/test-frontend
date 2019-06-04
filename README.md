# Wiredcraft Front-end Developer Coding Test

Make sure you read **all** of this document carefully, and follow the guidelines in it.

## Context

Use HTML, CSS, and JavaScript to implement the following mockup.

![wiredcraft-front-end-test-mock](https://cldup.com/JM3lLBAS5V.jpg)

[Mockup source Sketch file](https://cldup.com/2wo0ktkbxJ.sketch)

## Requirements

### Page Structure

```
Header(Navigation)

Main
  - Table Filter
    - Search Filter (dropdown component)
    - Search Keywords (input field)
  - Table
    - Table Header
    - Table Body
      - Table Row
        - Collapsable Row (State -> Distract -> Township)
          - State Level (Show by default)
            - District Level (Hide by default, show by clicking the button in state level)
              - Township Level (Hide by default, show by clicking the button in district level)
```

### Functionality

- Static page header (navigation bar), no extra features needed.
- The table filter needs to be able to filter the result in the table by the type and keywords.
- The table is nested, and grouped by state, district, township.

### Tech stack

- JS oriented
  - Use **React**.
  - Use CSS or SASS or any **CSS** framework as you like.
- CSS oriented
  - Use any **JS** framework as you like.
  - Use **SASS**.

### Bonus

- Write clear **documentation** on how it's designed and how to run the code.
- Provide proper unit tests.
- Write good commit messages.
- An online demo is always welcome.

## What We Care About

Feel free to use any libraries you would use if this were a real production App, but remember we're interested in your code & the way you solve the problem, not how well you can use a particular library.

We're interested in your method and how you approach the problem just as much as we're interested in the end result.

Here's what you should aim for:

- Good use of current HTML, CSS, and JavaScript & performance best practices.
- Solid testing approach.
- Extensible code.

## Q&A

> Where should I send back the result when I'm done?

Fork this repo and send us a pull request when you think you are done. We don't have a deadline for the task.

> What if I have a question?

Create a new issue in the repo and we will get back to you very quickly.

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
