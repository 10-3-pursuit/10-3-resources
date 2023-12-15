# Building React Components and Preventing Unnecessary Rerenders

### The videos show how:

- you would go about creating your own app by coding in App.jsx first and then moving relevant pieces of code to individual components
- components are triggered to re-render when we update state, sometimes unnecessarily
- we can move state that only cares about one component to that component and avoid unnecessary re-renders
- we lift state (or in our case leave state) so that 2 or more children can use the same state

## Videos:

- [App & React Rendering Introduction](https://drive.google.com/file/d/1ezBRVcCeDtTAd7ac2ITmNdaEfpzxjrzk/view?usp=sharing)- intro to the app where I code only in App.jsx and test the functionality first

- [Create Header & Footer Component](https://drive.google.com/file/d/1ihot-oPCQtEm0gCNRF3P8WkMHwkgrbGa/view?usp=sharing)- Now we begin to break code into components

- [Create NameList Component](https://drive.google.com/file/d/103tqw1AXpDVWWvTjWcGcOlo4QdKVhJT5/view?usp=sharing)- We move our (.map) list JSX to its own component and pass it props

- [Create Form Component](https://drive.google.com/file/d/1vDFebTSf49-papRbWZB9bm623ksrB-fE/view?usp=sharing)- We move all or our form JSX, realted functions, related state and we pass needed props to the Form component. This is where we :octagonal_sign: stop the Unnecessary Re-rendering

[Home][def]

[def]: README.md
