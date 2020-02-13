# Difference between props and states

 * [Props and states](https://lucybain.com/blog/2016/react-state-vs-pros/) are both variables but props are passed by its parent component whereas states are directly initailised and managed by a component.
 * states are initialised by props.
 * Ex:-
    - A parent component may include a child component by calling __< ChildComponent />__ and hence the parent can pass by __< ChildComponent color=green />__ and this can be accessed in the _child component_ by using a _child component constructor_
    i.e
    -  class ChildComponent extends React.Component {
    -       constructor( props) {
    -           super( props)
    -           console.log(props.color)
    -       }
    -  }
 * Props can be used to set the internal state based on a prop value in the constructor.
 * Props should never be changed in a child component.
 * State data is  maintained inside a component.The component will  update the state using the setState function.
 * State is owned locally , whereas Props are owned by a parent component and are read-only.