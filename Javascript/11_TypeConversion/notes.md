# Type Conversion 

- Type conversion in javascript refer to the automatic and explicit process of converting data from one data type to another data type.

1. Implicit Type Conversion 
2. Explicit Type Conversion 

## Implicit Conversion 

- When Javascript automatically done the type conversion.

```javascript

// Example: Converting to string

"100" + 24 // "10024"
"100" + null // "100null"


// Example: Converting to number 

"100" / 50 // 2
"100" * true // 100
"100" * false // 0
"100" * null // 
"100" * undefined // NaN
"LIT" / 2 // NaN


// Example: Converting to Boolean 

let num = !!0 //  
let res = !"" // 

```

## Explicit type conversion 


- When you convert the data type of a variable manually is called explicit type conversion.

```javascript 

// Example: 

String(100) // 
Number("100") // 
Boolean("") // 
parseFloat(10) // 
parseInt(10.556) // 

```