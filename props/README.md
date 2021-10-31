## Props
Props are basically the properties which are sent by an user.
It is given in the App.js and is used in the functional component.

## Proptypes
To define the type of the properties that are sent by an user, so that the user knows when the code shows an error. 
(Sometimes the user sends an object as an argument when the required prop should be a string so we get to know about that error in the console).

#### Syntax of proptypes
function_name.propTypes = {
prop1: propTypes.string,
prop2: propTypes.object
}

## Default Props
When there is no properties sent by an user, the default props are used so as to display some or the other content.

#### Syntax of defaultProps
function_name.defaultProps = {
prop1: 'Enter the default value',
prop2: 'Enter the second default value'
}

### isRequired
To specify if the feild is required or not. 
Commonly used in propTypes itself, shows an error if the user doesn't give the input for that particular string.

#### Syntax for isRequired
function_name.propTypes = {
prop1: propTypes.string.isRequired,
prop2: propTypes.object
}
