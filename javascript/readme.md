# HELLO WORLD 

```
<html lang="en">
<head>
    <script>
        console.log('Hello World')
    </script>
</head>
<body>
</body> 
</html>
```

# VARIABLES 
### Javascript variable are loosely types

## Vanila JavaScript
## using `var` 
 ```js
var myName = "JavaScript"
var myNumber = 20
var myFloat = 20.25
var myBool = true
 ```

## ES5 
## using `let` 
 ```js
let myName = "JavaScript"
let myNumber = 20
let myFloat = 20.25
let myBool = true
 ```

## using `const`

 ```js
const myName = "JavaScript"
const myNumber = 20
const myFloat = 20.25
const myBool = true
 ```

 ## Differences

 |Type|Difference|Mutability|
 -----|----------|----------|
 |`var`| Global Scope | Yes|
 |`let`| Local Scope | Yes|
 |`const`| Local Scope | No|

 ### Example for `var`
 ```js
 function foo(){
     var bar = "foo"
 }

 console.log(bar)
 ```
 **OUTPUT**
  ```
foo
 ```
 ### Example for `let`
 ```js
 function foo(){
     let bar = "foo"
 }

 console.log(bar)
 ```
 **OUTPUT**
  ```diff
  -ReferenceError: bar is not defined
 ```
  ### Example for `cosnt`
 ```js
const bar = "foo"
 
bar = 'something'

 console.log(bar)
 ```
 **OUTPUT**
  ```diff
  -TypeError: assignment to constant variable
 ```
 # Using `typeof` Operator
```js
var length = 16;                               // Number
typeof length
var lastName = "Johnson";                      // String
typeof lastName
var x = {firstName:"John", lastName:"Doe"};    // Object
typeof x
 ```
 **OUTPUT**
 ```
 number
 string
 object
 ```
 
  # Arrays
  ## Initalization
```js
//immediate initialization
var fruits = ['orange','banana','apple']
 ```
 ```js
var fruits = []
fruits = ['orange','banana','apple']
 ```
```js
 //Using new keyword
 var fruits = new Array("orange", "banana", "apple");
 ```
## USES
 ```js
 //Accessing all elements
 console.log(fruits)
 //Accessing using index
console.log(fruits[0])
 //changing value using index
 fruits[2] = 'Kiwi'

 ```
## Manipulations
### Adding new element to the array 
 


