# Function-scoping

function foo() {
 var a = 'hello';
 function bar() {
 var b = 'world';
 console.log(a); // => 'hello'
 console.log(b); // => 'world'
 }
 console.log(a); // => 'hello'
 console.log(b); // reference error
}
console.log(a); // reference error
console.log(b); // reference error
