# mad9014-w24-hybrids (objects)
1. Copy the following code snippet and convert all the dot notation into square bracket syntax.
```js
const obj = {
  a: 'first letter',
  b: 123,
  c: true,
  d: [
    { id: 11, name: 'emilia' },
    { id: 22, name: 'tessa' },
    { id: 33, name: 'naomi' },
  ],
  e: {
    age: 17,
    email: 'bob@home.org',
  },
};
//convert the lines below here
console.log(obj.a);
console.log(obj.d[1].name);
console.log(obj.e.age);
```
2. Declare an object, person, with the following properties:
* firstName (string)
* lastName (string)
* age (number)
* isStudent (boolean)
3. Add a new property, city, to the person object with a string value.
* Print the person object to the console.
* Use the delete operator to remove the isStudent property from the person object.
* Print the updated person object to the console.
4. Declare an object, car, with properties like make, model, year, etc. Use a for...in loop to iterate over the properties of the car object and print them to the console.
5. Create a function that accepts an Object and a String as arguments. The function then needs to check if the Object has a property with a name that matches the String argument. Use hasOwnProperty() to check for existence. If it does then use delete to remove the property.
