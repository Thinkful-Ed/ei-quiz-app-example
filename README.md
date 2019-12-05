#### Students are expected to build their EI Quiz apps utilizing the following methods:

1. All data should be stored in a centralized data STORE (variable).
2. No HTML should exist in the `index.html` file that will not visibly persist throughout the entirety of the application.
3. All HTML should be generated using template generation functions (see examples in [index.js](https://github.com/Thinkful-Ed/ei-quiz-app-example/blob/master/scripts/index.js)).
4. The STORE should only be updated by event handler functions (see examples in [index.js](https://github.com/Thinkful-Ed/ei-quiz-app-example/blob/master/scripts/index.js)).
5. The page should be re-rendered anytime the STORE is updated by calling one singular `render()` function that will conditionally render the page based upon the state of the STORE.

You may use the application in this repository as an example, but **please do not share its code with EI students**.