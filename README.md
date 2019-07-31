# ReactJS Testing

Run the following command to get a basic ReactJS application setup:

```
npx create-react-app my-app
cd my-app
yarn start
```

The basic ReactJS comes with a testing library, but we will be working with another to give you more functionality.

1. Setup Jest

* Within the my-app folder, run:

```
npm install --save-dev jest
```

* Update the package.json file to have the following for the "test" line:

```
    "test": "jest"
```

* In order to be able to use ES6 methods within your test, you will need to install Babel for Jest with the following command:

```
yarn add --dev babel-jest @babel/core @babel/preset-env
```

2. Add Redux & Test Reducer

* Use what you learned previously on Redux to install it

* Create a reducer that just returns initial state

* Create a unit test for the reducer

* Confirm that the test passes.

3. Test Action

* Create an action that returns a constant type and a payload

* Create a unit test for the action

* Update the reducer you created previously to update the state for the action's type and payload.

* Update the unit test for the reducer to handle this new case

* Confirm that the test passes.

4. Test with Snapshot

* Update the App.test.js to have a new test that says it matches the snapshot.

* Arrange the test by creating an instance of the App class

* Act upon the instance by calling it's render function and storing that into a variable.

* Assert that the results of the render matches the snapshot.

* Confirm that the test passes.

5. Mock library with jest

* Install moment JavaScript library

* Use the library in the App.js file.

* Mock out the library using jest.mock

* Mout out the library using a file in __mocks__/moment.js

6. Test event handlers

* Add an onClick event handler to the App.js file

* Create a test for the onClick event handler

7. Testing Async/Promises

* Add a fetch request in the App.js file with a then and a catch

* Create a test for the success case

* Create a test for the failure case

8. Create Test Database

* Install @shelf/jest-mongodb

* Update your Jest configuration to use a preset

* Write a test to insert a profile into a collection

After you have completed all of the exercises, commit your changes with the following command:

```
git commit -am "ReactJS Testing Examples"
```
