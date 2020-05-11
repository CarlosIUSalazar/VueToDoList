# Week 5 Assessment

Covers some important concepts covered in week 5

- Vue
- CI/CD
- React vs. Vue

You will be allotted 1 hour for this assessment. A pull request must be made before the 1 hours is over.

We highly suggest looking through everything first and making sure you have enough time for each part.

## Rules

1.  **You are only allowed to use the following resources:**

    - [MDN](https://developer.mozilla.org/en-US/)
    - [Vue Docs](https://vuejs.org/v2/guide/)
    - [Heroku Docs](https://devcenter.heroku.com/)
    - [React Docs](https://reactjs.org/docs/)

1.  **You are NOT allowed to look at or use any previously written code (whether by you or someone else).**

    - **Copy/Pasting previous code and simply renaming some variables is still considered cheating and will have serious consequences.**
    - **Likewise, answering questions by copy/pasting text from official resources is considered cheating**
      - Use your own words and thoughts to answer questions.

1.  Remember to give yourself a grade for each problem.
1.  Tests are optional, but highly encouraged.

## Pull Requests

Please remember to submit the [Assessment Questions and Survey](https://forms.gle/cAeqtAtmifZKFFdr5) before submitting your Pull Request

Feel free to include other comments you would like.

## Requirements

Read through and understand **all** of these before starting work. If anything is unclear, flag down an Instructor immediately.

You will notice that some questions are marked as **Intermediate** these are not mandatory so feel free to skip, but answering them allows us to better judge your knowledge and understanding.

1.  Questions - React vs Vue

    - Answer all of the questions in the [Assessment Questions and Survey](https://forms.gle/cAeqtAtmifZKFFdr5)
    - Use code when possible to explain your answer

1.  Vue

    - Add your name to the `App` component so that your app displays “YourName’s Task List”.
    - Connect the `Task` component to the `TaskList` component so that it renders each item in the task list.
    - Add a directive to the button in the `Task` component so it toggles `isComplete` when pressed. If you have done this correctly, clicking on the button will cross out an item in your list.

1.  CI/CD

    - Please create a Heroku app from this repository on your account, then invite instructors as collaborators to your heroku project.
      - Add `felix@codechrysalis.io`, `melvin@codechrysalis.io`, and `dustin@codechrysalis.io` as collaborators.
      - Accessing your Heroku app should show the same as if you were to run `yarn start` on your local machine. In other words, your deployed Heroku app should look the same as running your app on your own computer.
      - Last, update `./heroku/index.js` with the link to your Heroku app.
      - Hint: you may need to set your NODE_ENV to "development" in your config variables

1.  Advanced - Vue (OPTIONAL)

    - Create an input that allows the user to add a new item to your task list.


## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn dev
```

### Compiles a static build and runs a simple production server
```
yarn start
```

### Lints and fixes files
```
yarn lint
```

## What We Look For

Your understanding of the material will be rated through:

- the quality of your commits
- if your code works
- code style and organization
- explanations given
