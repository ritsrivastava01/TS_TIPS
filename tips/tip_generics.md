### Generics
Generics are create a component that can work over a variety of types rather than a single one. 
This allows users to consume these components and use their own types.
Genrice is special type variable <T>, which works on type of the variable. 
```
function identity<T>(arg: T): T {
    return arg;
}
```
we can alspo use any like
```
function identity(arg: any): any {
    return arg;
}
```
but function accept 'any' data type like 'string' and return 'any' type like 'number', hence we are loosing information.
but with ```Genric``` function is accepting same type <T> and return same type <T>, T can be string, number etc.

we can use above genric function in our code like
```
let output = identity<string>("myString");  // type of output will be 'string'
```
OR
```
let output = identity(36);  // type of output will be 'number'
```
please notice we didn't use angle brakets (<>), 
becouse compiler just looked at passed valued and set "T" to its type. 
