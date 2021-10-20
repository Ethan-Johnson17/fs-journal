# JavaScript
JS is linked with <script src="app.js"></script> and should be at the bottom of the <body>

Console.log to test whether the JS connected properly

undefined is not defined. null is no value

Reference types: array [] and object {}
Both hold data, the difference is how the data is accessed. 
Array store data by their position or INDEX 
console.log('array', array[1]);

Objects store their data by KEY/PROPERTY and VALUE
console.log('object', object[key], object.key)

'Ethan' is a primitive value type, {name: 'Ethan'} is an object. It contains a VALUE and KEY. 

Types of reassignment include:
x++
x =+ 10
++x
x = 'string'

++sum is pre-operative
sum++ is post-operative

concat essentially glues strings together
interpolation allows you to inject things into a page

Debugger lets you pause mid code and see whats happening

functions don't run until it's called or invoked.

Parameter is the placeholder, argument is the value when the function ias actually called.
The parameters are what the "monster" knows the value as.

bang.sugar ? 'has sugar' : 'is sugar free' is the same as if/then statement. Turnary
^ this is a boolean value. 

array.join(' ') turns array into a string and seperates with what is put in the ' '

const cat = cats[i]; <-this is accessing the first value in the array cats[]

forEach loop will go through every element regardless. For loops will have a break point.
cats.forEach( cat => {
    console.log(cat)
})

let found = ' '
for (let i=0; i< cats.length; i++) {
    const cat = cats[i]
    if (cat.name === 'patches') {
        found = cat
        break
    }
}
⬆ is the same as  ⬇
let found = cats.find(cat => cat.name === 'patches') 

'?' is used to drill safely into a complex object to find a class that may not exist on all elements being searched

let foundTopping = toppings.find

Arrays use find and other methods to access elements. Dictionaries can access elements with name/key
let foundTopping = toppingsDict[choice] <- dict method of
let foundTopping = toppings.find(topping => topping.name ==choice) <- array method

Establish the facts first, then write the function. Break it down into the most simple terms.