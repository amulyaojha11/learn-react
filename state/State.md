# State in React

It has the update of the state that a particular component is in. 
Hooks were basically used to provide the class component features in functional component.

## useState hooks in React

useState is used to preserve the values between the function calls.
It has 2 parts, one is the state variable and the other is the state function.
The state function is used to change/update the values of the state variable.

### Importing the useState hook in React

```
import 'useState' from 'react'
```

### To declare a useState variable and change the value of state variable

```
const [text, setText] = useState("initial value");
setText("Amulya");
```
This changes the value of text from "initial value" to "Amulya".

#### Note
useState is similar to this.state in class component.
