# Stateless components

* Stateless components are the one which doesn't keep track of the changing data ,instead they print those which are passed to them via props.
* They always render same thing.
* Ex: 
 const BooksList = ({books}) => {
 return (
   <ul>
     {books.map(book => {
       return < li>book< /li>
     })}
   </ul>
  )
 }

* In the above example of [stateless](https://programmingwithmosh.com/javascript/stateful-stateless-components-react/) component its often written as function.
* Making a component stateless will make other component reuse them multiple times.
* Stateless component doesn’t even take props,but we should always have a child component to display a input via props.
* They are always reusable.