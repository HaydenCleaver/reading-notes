# Class 3

These readings are important because they give us more tools to manipulate objects and arrays and to iterate over them more easily.  The video explains how we can get components to interact with each other.

## React - Lists and Keys

1. `.map()` takes an array and returns a new one.

2. if you want to display the values of an array in JSX, you can use .map() to loop through the array and return the new array values to a list.

3. Each list item requires a unique key.

4. Keys help you identify what items in a list have been added or changed.

## Spread Operator

1. The spread operator `...` will 'spread' an array (or object), allowing seperate agruments within it to be read individually.

2. the spread operator can also:
    * Copy an array
    * Concatenate or combine arrays
    * Add an item to a list
    * Combine objects
    * Convert NodeList to an array

Reference: [Medium](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

3. 
    `arr1 = ['a', 'b', 'c']`<br>
`arr2 = ['d', 'e', 'f']`<br>
`arr3 = [...arr1, ...arr2]`

4. `const fewFruit = ['ð','ð','ð']` <br>
`const fewMoreFruit = ['ð', 'ð', ...fewFruit]`<br>
`console.log(fewMoreFruit) //  Array(5)`<br> 
`[ "ð", "ð", "ð", "ð", "ð" ]`<br>
Reference: [Medium](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

5.
    `[...["ððððĪŠð"]] // Array [ "ððððĪŠð" ]`<br>
`[..."ððððððĨ°ððĪĐ!"] // Array(9) [ "ð", "ð", "ð", "ð", "ð", "ðĨ°", "ð", "ðĪĐ", "!" ]`<br>

    `const hello = {hello: "ððððĪŠð"}`<br>
`const world = {world: "ððððððĨ°ððĪĐ!"}`<br>

    `const helloWorld = {...hello,...world}`<br>
`console.log(helloWorld) // Object { hello: "ððððĪŠð", world: "ððððððĨ°ððĪĐ!" }`<br>

Reference: [Medium](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## Passing Functions Between Components

1. He creates a function and assigns it a variable to be passed to another componenent as a prop. 

[Return to Table of Contents](https://haydencleaver.github.io/reading-notes/)