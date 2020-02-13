# Class Component

* A class component requires you to extend from React. Component and create a render function which returns a React element.
* Ex:
    - class Welcome extends React.Component {
    -   render() {
    -    return < h1>Hello, { this.props.name}< /h1>;
    -   }
    - }
* [ClassComponent](https://dev.to/iam_timsmith/class-components-vs-stateless-functional-components-51he) allows us to use setState() .
* In a class component we can setState() by passing a fucntional component via props from the parent component.
* We can use the life cycle methods from the React.component.
* we can create custom functions to use in our component and take advantage of lifecycle methods, So that they help during storing and manipulation of data.