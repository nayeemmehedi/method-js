# method-js

/**
https://www.youtube.com/watch?v=Mr5W7bQOhYs
 song
 
 
 
 * //array method..
 * https://www.programiz.com/javascript/library/array/isarray
 * 
 * 1.concat
 * const array1 = ['a', 'b', 'c'];
const array2 = ['d', 'e', 'f'];
const array3 = array1.concat(array2);

console.log(array3);
// expected output: Array ["a", "b", "c", "d", "e", "f"]

   3.every

   const isBelowThreshold = (currentValue) => currentValue < 40;

     const array1 = [1, 30, 39, 29, 10, 13];

     console.log(array1.every(isBelowThreshold));
     // expected output: true

   4.fill


   const array1 = [1, 2, 3, 4];

// Fill with 0 from position 2 until position 4
console.log(array1.fill(0, 2, 4));
// expected output: Array [1, 2, 0, 0]

// Fill with 5 from position 1
console.log(array1.fill(5, 1));
// expected output: Array [1, 5, 5, 5]

console.log(array1.fill(6));
// expected output: Array [6, 6, 6, 6]


   5.filter
   6.find

   The find() method returns the first element

   const array1 = [5, 12, 8, 130, 44];

const found = array1.find(element => element > 10);

console.log(found);
// expected output: 12

   7.findIndex

   The findIndex() method returns the index of the first element
   
const array1 = [5, 12, 8, 130, 44];

const isLargeNumber = (element) => element > 13;

console.log(array1.findIndex(isLargeNumber));
// expected output: 3

   8.forEach
  9.includes

  const array1 = [1, 2, 3];

console.log(array1.includes(2));
// expected output: true

const pets = ['cat', 'dog', 'bat'];

console.log(pets.includes('cat'));
// expected output: true


  10.indexOf

  const beasts = ['ant', 'bison', 'camel', 'duck', 'bison'];

console.log(beasts.indexOf('bison'));
// expected output: 1


  11.join

 const fruits = ["Banana", "Orange", "Apple", "Mango"];
let text = fruits.join(" and ");

output Banana and Orange and Apple and Mango

  
  15.pop

  const plants = ['broccoli', 'cauliflower', 'cabbage', 'kale', 'tomato'];

console.log(plants.pop());

  16.push

const count = animals.push('cows');
console.log(count);
// expected output: 4
console.log(animals);
// expected output: Array ["pigs", "goats", "sheep", "cows"]


  17.reduce

  const array1 = [1, 2, 3, 4];

// 0 + 1 + 2 + 3 + 4
const initialValue = 0;
const sumWithInitial = array1.reduce(
  (accumulator, currentValue) => accumulator + currentValue,
  initialValue
);

console.log(sumWithInitial);

// expected output: 10

  18.reverse

  const array1 = ['one', 'two', 'three'];

const reversed = array1.reverse();
console.log('reversed:', reversed);

// expected output: "reversed:" Array ["three", "two", "one"]

  19.shift

  const array1 = [1, 2, 3];

const firstElement = array1.shift();

console.log(array1);
// expected output: Array [2, 3]


 20.slice
 const animals = ['ant', 'bison', 'camel', 'duck', 'elephant'];

console.log(animals.slice(2));
// expected output: Array ["camel", "duck", "elephant"]

console.log(animals.slice(2, 4));
// expected output: Array ["camel", "duck"]

console.log(animals.slice(1, 5));
// expected output: Array ["bison", "camel", "duck", "elephant"]

console.log(animals.slice(-2));
// expected output: Array ["duck", "elephant"]

console.log(animals.slice(2, -1));
// expected output: Array ["camel", "duck"]

console.log(animals.slice());
// expected output: Array ["ant", "bison", "camel", "duck", "elephant"]


 21.some

 const array = [1, 2, 3, 4, 5];

// Checks whether an element is even
const even = (element) => element % 2 === 0;

console.log(array.some(even));
// expected output: true


 22.sort

 const months = ['March', 'Jan', 'Feb', 'Dec'];
months.sort();
console.log(months);
// expected output: Array ["Dec", "Feb", "Jan", "March"]

 23.splice

 const months = ['Jan', 'March', 'April', 'June'];
months.splice(1, 0, 'Feb');
// Inserts at index 1
console.log(months);
// expected output: Array ["Jan", "Feb", "March", "April", "June"]

 24.toString

 const array1 = [1, 2, 'a', '1a'];

console.log(array1.toString());
// expected output: "1,2,a,1a"


 25.unshift
 const array1 = [1, 2, 3];

console.log(array1.unshift(4, 5));
// expected output: 5

console.log(array1);
// expected output: Array [4, 5, 1, 2, 3]

 26.Array.isArray

 The isArray() method checks whether the passed argument is an array or not.

 let numbers = [1, 2, 3, 4];

// checking whether numbers is an array or not
console.log(Array.isArray(numbers));


 * 

 //object method
 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries

 1.Object.assign()
 const obj1 = { a: 1 };

  const new_obj = Object.assign({}, obj1);





 3.Object.entries

  const obj = { 10: 'adam', 200: 'billy', 35: 'chris' };

    console.log(Object.entries(obj));

    for(const [key,value] of obj)

  


 4.Object.keys
 const object1 = {
  a: 'somestring',
  b: 42,
  c: false
};

console.log(Object.keys(object1));
// expected output: Array ["a", "b", "c"]

 5.Object.values

 const object1 = {
  a: 'somestring',
  b: 42,
  c: false
};

console.log(Object.values(object1));
// expected output: Array ["somestring", 42, false]

 */
