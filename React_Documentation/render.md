# Render()

 * Syntax:-
    - render()
 * This  is the only method in a class component.
 * The render() examine either this.props or this.state and __returns__.
 * A return may include react elements,array and fragments,strings,numbers ans so on...
 * The render() doesn't interact with the browser directly and returns the same result each time when it gets invoked.
 * React life cycle method should be invoked if browser [interaction](https://reactjs.org/docs/react-component.html) is required.