# __React Component four stages of its life__

*Four stages of its life*

 1. Initialization
 2. Mounting
 3. Updating
 4. Unmounting

## __Initialization__
    _This is the stage where the component is constructed with the given Props and default state._
    Here we define all the props and set the state and done by defining a constructor.

    EX:
        constructor(props){
            this.state = state
        }


    
## __Mounting__
    _Mounting is the stage whuch includes rendering the JSX returned by the render method itself._
    In mounting the component is rendered into the dom and rendered for the webpage.
    
        componentWillMount():means that the function is invokes just before the component is mounted on the DOM i.e. before the render function is executed.
    
        componentDidMount():means that the function is invokes just after the component is mounted on the DOM i.e. after the render function is executed

## __Updating__
    _Updating is the stage when the state of a component is updated. -
    In Updation is where the components are updated by various events such as clicking, pressing a key on keyboard and so on.
    Various functions that are invoked at different point of view are:-
        I) componentWillRecieveProps():-
            This function doesn't have any  states and is invoked before the mounted component gets its props reassigned . Though the props is simliar or not the function willbe passed.
        
        II) setState():-
            The set state function can be invoked at any point of time explicitly .Its used to update the state of the component.
        
        III)shouldComponentUpdate():-
            This function allows React to know whether the component’s output will be affected by the update or not. It is invoked before rendering an already mounted component when new props or state are being received. Its argument consist of new Props and new State and decides to re-render or not.
        IV)componentWillUpdate():-
            This function gets invoked once before the render() function is executed after the updation of State or Props.
        V)componentDidUpdate():-
            Once the render function is executed  and State or Props is updated after that componentDidUpdate() will get executed.

## __Umounting__
    _Unmounting is the final step of the component lifecycle where the component is removed from the page_ 
    It consist of the method componentWillUnmount():-
        This function is invoked once before the component is removed from the page
