# Useful Things...

### Material UI Site:
starter guide
1) https://material-ui.com/ 
2) https://material-ui.com/components/rating/

### css:
1) https://www.muicss.com/docs/v1/react/
2) For Components and box
   https://material-ui.com/components/box/

### font awesome latest import guides:
https://www.npmjs.com/package/@fortawesome/react-fontawesome

### to display the word document in the react Application:

### to get the data into a table component.... using react-table component
https://www.positronx.io/how-to-build-react-data-table-with-react-table-package/

### for Creating a form...
https://jasonwatmore.com/post/2020/02/08/react-formik-2-form-validation-example

### creating form with formik, materialui and yep...
https://dev.to/finallynero/react-form-using-formik-material-ui-and-yup-2e8h

### for printing the json in the ui 
<pre> {JSON.stringify(values, null, 2)}</pre>

### CSS Guide: scotch: io
https://scotch.io/tutorials/deep-dive-into-css-grid-2?utm_source=newsletter&utm_medium=email&utm_campaign=using_react_hooks_webinar_custom_apis_w_airtable&utm_term=2020-05-14


### for adding and removing columns 
https://codesandbox.io/s/0pp97jnrvv?file=/src/index.js

### to fetch the data using axios and load it to store
https://dev.to/markusclaus/fetching-data-from-an-api-using-reactredux-55ao

### to setup saga for making efficient Async call
https://redux-saga.js.org/docs/introduction/BeginnerTutorial.html
https://blog.logrocket.com/understanding-redux-saga-from-action-creators-to-sagas-2587298b5e71/   [Nice](implementation for normal without middleware, thunk & saga)

https://medium.com/@shrsujan2007/implementation-of-redux-saga-in-react-applications-973f5a2a87d2  [**** Nice ]

example of Material ui with react all types of components:
https://www.golangprograms.com/example-of-react-js-with-material-ui-components.html


### Best way to debug like the above line...
  {JSON.stringify(
                        {
                            pageIndex,
                            pageSize,
                            pageCount,
                            canNextPage,
                            canPreviousPage,
                            sortBy,
                            groupBy,
                            expanded: expanded,
                            filters,
                            selectedRowIds: selectedRowIds,
                        },
                        null,
                        2
                    )}

### Test the formik values like this...
 VALUES:
          <pre>{JSON.stringify(formik.values, null, 2)}</pre>
          ERRORS:
          <pre>{JSON.stringify(formik.errors, null, 2)}</pre>
          TOUCHED:
          <pre>{JSON.stringify(formik.touched, null, 2)}</pre>

### Integrating with FORmik with material-ui : 
https://dev.to/finallynero/react-form-using-formik-material-ui-and-yup-2e8h

### For Bucket Assignment and Un-Assignment ->  Picture
https://ux.stackexchange.com/questions/30049/best-ui-pattern-for-letting-a-user-assign-items-to-

### For handling multiple checkbox...
https://medium.com/@patilharsh555/build-a-reusable-checkbox-group-component-in-react-with-material-ui-63823f13eafa
https://stackblitz.com/edit/react-chkbx-grp?file=App.js

https://codesandbox.io/s/328038x19q?file=/src/index.js

### For API Call Pattern to retrieve the data...
https://blog.logrocket.com/patterns-for-data-fetching-in-react-981ced7e5c56/

### For Immutability of Redux state, this is a good example...
https://daveceddia.com/react-redux-immutability-guide/

### Nice Example better than everything else [REDUX, REACT, SAGA]...
https://github.com/wtjs/what-the-splash

### React-Redux - crud example - how to update without manipulating the state...***
https://codeburst.io/redux-a-crud-example-abb834d763c9

### How to perform the axios call in the saga for a get Method...
https://stackoverflow.com/questions/52219839/how-to-pass-urls-params-headers-to-call-in-redux-saga

### Flow of Application:
https://stackoverflow.com/questions/50151277/react-redux-saga-boilerplate-flow

### selector Example:
https://medium.com/@matthew.holman/what-is-a-redux-selector-a517acee1fe8

### Dialogue Example:
https://codesandbox.io/s/ciffn?file=/demo.js    - Max Width - Good and looks nice
https://codesandbox.io/s/4xlrs?file=/demo.js    - Scroll Paper, Scroll Body

### ERROR:

1) To enable the application in other browsers, you have to disable the dev tools...
https://github.com/reduxjs/redux/issues/2359 

#### Fastest way to filter the data in js [Comparison chart]
https://medium.com/javascript-in-plain-english/how-to-remove-a-specific-item-from-an-array-in-javascript-a49b108404c
