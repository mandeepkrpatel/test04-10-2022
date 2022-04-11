Q 1 ans - ES6 stands for ECMAScript 6. ECMAScript was created to standardize JavaScript, and ES6 is the 6th version of ECMAScript, it was published in 2015, and is also known as ECMAScript 2015.
New Features in ES6 :-
1. The let keyword - Variables defined with let cannot be Redeclared.
      Variables defined with let must be Declared before use.
           example - let x = "Saurav";
                     let x = 0;
                     // SyntaxError: 'x' has already been declared
2. The const keyword- The const keyword allows you to declare a constant.   
Consta value cannot be changed.A const variable cannot be reassigned.
example -  const x = 10;
                 x = 6;      // This will give an error
                 x = x + 10;   // This will also give an error 
3. Arrow Functions - Arrow functions allow us to write shorter function syntax
example -  hello = () => {
                          return "Hello World!";
                          }              
 4. For/of - The JavaScript for in statement loops through the properties of an Object.
  const person = {name:"Mandeep", Lname:"Kumar", age:24}; 
       let txt = " ";
          for (let x in person) {
               txt += person[x] + " ";
                }

for of loop - It invokes a custom iteration hook with statements to be executed for the value of each distinct property of the object.
example -
const array1 = ['a', 'b', 'c'];

for (const element of array1) {
  console.log(element);
}

// expected output: "a"
// expected output: "b"
// expected output: "c"

5.Map Objects - The Map object holds key-value pairs and remembers the original insertion order of the keys. Any value (both objects and primitive values) may be used as either a key or a value. 
example - 
const map1 = new Map();

map1.set('a', 1);
map1.set('b', 2);
map1.set('c', 3);

console.log(map1.get('a'));
// expected output: 1

map1.set('a', 34);

console.log(map1.get('a'));
// expected output: 34

console.log(map1.size);
// expected output: 3

map1.delete('b');

console.log(map1.size);
// expected output: 2