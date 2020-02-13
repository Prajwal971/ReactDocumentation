# Extending a react component

__Extending a Component allows us to pass props(_properties that are  being used for passing data from one component to another_) to a user defined class when a constructor is not present like it is in the App class.
Functons like setState() can also be defined which can be inherited to any other class whoch extends the component.__

Ex:

class Component {
        constructor(props) {
            this.props = props
        }
    
        setState(partialState) {
            
        }    
    } 
    
    class App extends Component {
        render() {
            return React.createElement('div', null, this.props.message )
        }
    }
    
    const appInstance = new App({ message: "hey I am accessible" })
    console.log(appInstance.props.message) // => "hey I am accessible"
    console.log(appInstance.setState) // => [Function: setState]

