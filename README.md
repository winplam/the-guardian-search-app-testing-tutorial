# tutorial-the-guardian-search-app

This repo is created following the instructions from this tutorial on [how to test React components using Jest and Enzyme](#).
1.  **unit-testing** - unit testing for Search and SearchResults components
2.  **integration-testing** - integration testing for SearchContainer component

## Functional App Branch
1.  Run `npm install`
2.  Create `config.js` file and include the following:
    ```
    export const API_KEY = "YOUR_API_KEY";
    ```
    You need to obtain the API key from the [Guardian website](http://open-platform.theguardian.com/access/) by signing up. Copy and paste your key where it says **YOUR_API_KEY**.
3.  Run `npm start` to start the server
