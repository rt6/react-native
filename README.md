# REACT-NATIVE

### Start new project
You will need to instal Xcode before you can run IOS simulator

```sh
$ npm install -g react-native-cli
$ react-native init newAPP 
$ cd newAPP 
$ react-native run-ios
```

After simulator appears, press `Command⌘ + R` and select `Enable Live Reload`

### Start writing app
```sh
$ vi newAPP/index.ios.js
```



# 1) REDUX


Redux provdes a single state for your entire application so you do not need to pass state information from parent components to child components.   Every component has access to the *store* that contains the current app state.  Redux requires boilerplate to setup, but could be worth it for large apps.

## Concept
Redux is a design pattern to manage application state which can be hard to manage and predict when there are many async functions, events and indirectly associated UI components.  Pure functions do not have side effects, the same input will have the same output.  The idea is that components dispatch events to the store, and the store will use the reducer functions to calculate the new state based on the events received.  

## Terms
- **Store**: a JSON object that stores the current application state 
- **Actions**: a function that when invoked by components (eg. button) will return a JSON object containing the action type (name) and additional data (data for the reducer function). 
- **Reducers**: functions that change the state of the store based on the output returned from actions
- **Container (components)**: *connects* the store with the components by mapping redux store states to components props, and action functions (action creators) to component props.

## Code structure
```js
./app.js
./app/components/button.js
./app/reducers/index.js
./app/reducers/reducer.js
./app/actions/index.js
./app/actions/action1.js
./app/screens/screen1.js
```


# 2) SCREEN NAVIGATION

### Tab Navigator
Provides tabs at the bottom and top of the screen.

```js
coming soon
```

### Stack Navigator
Allows navigation of screens like a stack so you can go back (pop from the stack)
```js
```

# 3) ICONS
```js
coming soon
```


