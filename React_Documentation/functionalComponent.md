# Functional Components

 * A Functional component is a class component but without a render function.
 
 * Ex:
   - import React from 'react';
   - function App() {
   - const greeting = 'Hello Function Component!';
   - return < h1>{greeting}< /h1>;
   - }
   - export default App;

 * In the above example the word greeting is enclosed with {} and act as a simple as javascript and the variable __greeting__ is rendered and returned as a HTML headline.
 * Functional components are easier to read, debug, and test. They offer performance benefits, decreased coupling, and greater reusability.
 * Any state is reffered as "something" rather than "this.somethig".
 * A functional component is just a plain JavaScript function which accepts props as an argument and returns a React element.
