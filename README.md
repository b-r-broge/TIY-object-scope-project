## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.

 - Scope is what variables and functions are visible from any given place.  Some scopes are global, and can be read across the file, others are local and contained within a function.  
 - Hoisting is javascript's method of pulling variable declarations to the top of the function or file to ensure that variables are declared before being set.
 - Compartmentalization is the process of ensuring that you don't have conflict of variables or functions in your scope.

### Provide examples for all three, below:

#### Scope:
 function a () {
   let b = x;
 }

 console.log(b); // would error, since this console.log is outside of the scope of b

#### Hoisting:
 - see explanation above.

#### Compartmentalization:
 - see explanation above.
