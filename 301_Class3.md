# Class 3

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

4. `const fewFruit = ['🍏','🍊','🍌']` <br>
`const fewMoreFruit = ['🍉', '🍍', ...fewFruit]`<br>
`console.log(fewMoreFruit) //  Array(5)`<br> 
`[ "🍉", "🍍", "🍏", "🍊", "🍌" ]`<br>
Reference: [Medium](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

5.
    `[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]`<br>
`[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]`<br>

    `const hello = {hello: "😋😛😜🤪😝"}`<br>
`const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}`<br>

    `const helloWorld = {...hello,...world}`<br>
`console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }`<br>

Reference: [Medium](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## Passing Functions Between Components

1. He creates a function and assigns it a variable to be passed to another componenent as a prop. 