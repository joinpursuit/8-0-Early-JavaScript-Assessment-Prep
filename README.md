# Preparation for the Early JavaScript Assessment/Extra Fundamentals Practice

## Drills

Drills are an excellent way to practice syntax and solidfy your fundamentals. 

A critical part of preparing for a coding assessment, whether in class or for a job is to practice coding. Reading and watching videos helps a little, actually coding helps a lot. This can be a little bit difficult to get used to, sometimes we want to understand things better before trying. But the trying will really help you understand. 


### Errors

Copy and paste into repl.it and fix:

```js
console.log("Making your way in the world today takes everything you've got.");
console.log("Taking a break from all your worries, sure would help a lot."
console.log('Wouldn't you like to get away?');
console.log("Sometimes you want to go");
console.log("Where everybody knows your name,");
console.lo("and they're always glad you came.")
console.log("You wanna be where you can see,";
console.log("our troubles are all the same")
console.log("You wanna be where" "everybody knows");
console.log("Your name".)
```

### Make it True


```js
console.log(typeof '1' === 'number')
console.log(typeof 1_000 === 'string')
console.log(typeof 'true' === 'boolean')
console.log(typeof 'undfined' === 'undefined')


// BONUS

console.log(typeof null === 'null')
````

### Variables

Without running the code, type in what each final value is

```js
let f = '';
let g = 'my kazoo';
let h = "I'm just playing";
let l;

f = g;
g = h;
h = l;
l

// The final value of f is 
// The final value of g is
// The final value of h is 
// The final value of l is
```

Run the code and then compare and contrast your answers

Once again

```js
let a1 = '';
const b2= 'the chips';
let c3 = "Pass";
const a1;

a1 = b2;
b2 = c3;
c3 = a1;
a1;

// The final value of a1 is 
// The final value of b2 is
// The final value of c3 is 
// The final value of a1 is
```

What happned? Why did this one not turn out the same? Can you fix the code?


### Mathy

Console.log each mathmatical operation

```js
const q = 0
const p = ''

// Add 1 to p

// Add 2 tp q

// Multiply 10 times p

// Muliply 10 times q

// Divide p by 3

// Round p down


```

What is the final value of p?

What is the final value of q?


### String Combinations

Create a variable called `yourname` and assign your name to it

Create another variable called `greeting` and assign `Hello, my name is ` to it

Create a final variable called `ending` and assign `, nice to meet you!`

Now combine the strings so that it prints out (assuming your name is `Jean Jeanie`

`Hello, my name is Jean Jeanie, nice to meet you!`

## Make it True, Part 2

```js
  const a = 3;
  const b = 2_200;
  const c = -5;
  const d = 3.0;
  const e = 'String Bean';
```
[Comparision Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators)

Change the all of the `===` operators to another opereator in order to make each of these true:

```js
console.log(a === b);
console.log(c === d);
console.log(a === b === c);
console.log(a === a === d);
console.log(e === 'String Bean');
console.log(e === 'string bean');
```

### The Farm

Create a variable called `animal`

Write code that will print out `moooooo` if the variable `animal` is equal to cow.

Change your code so that if the animal is not a cow, it will print `This animal is not a cow`

Create a new variable `chickens`

Write code that will print the following statements based on the conditions provided:
 - If there are 13 chickens `All my chickens are here`
 - Else, if there are less than 13 chickens print out `Uh oh! Where is everyone?`
 - Else, if there are more than 13 chickens print `This seems suspicious, but I am ok with it!`
 - Else, if there are less than 0 chickens print `Error! I don't think we are in Kansas any more`



### Pot Luck Problems!

There was some miscommunication and too many people are bringing potato salad! Let's reassign some dishes!

```js
const dishes = ['potato salad', 'gulash', 'potato salad', 'cherry cheesecake', 'potato salad', 'deviled eggs', 'potato salad']

```
- Use a method to remove the last potato salad
- Use a method to remove the first potato salad
- Access the first occurance of potato salad using square brackets `[]` and reassign it to your favorite dish
- Add a new dessert to the end of the array
- Someone better bring napkins! Add those to the front of the array

### Objects

Create an object called `myPrecious`
Add the following keys and put in the properties that describe the object

- name
- What is it?
- color
- What shape is it?
- How big is it?

console.log the entire object
console.log just the color 

Change the property name to be `My precious!`

console.log the entire object again


Accessing Properties:

```js
const planet = { name: "Jupiter", ringSystem: true, moons: ["Europa", "Ganymede", "Io", "Callisto"] },

```

- Access and console.log the name
- Access and console.log the moons
- Access and console.log the moon `Io`
- Add `Endor` to the moons array, console.log to confirm 

### Loopin' It

- Write a loop that will print out the numbers from 1 - 100 using a while loop
- Write a loop that will pring out the numbers from 1 - 100 using a for loop
- Write a loop that will print out the numbers from 50 - 500
- Write a loop that will print the numbers starting from 1000 down to 944

### Get Even

Write a loop that will print out the even numbers from -10 to 10 by changing the increment/decrement value

### Get odd

Write a loop that will print the odd numbers by using an if statement

### Fizz Buzz 

Write a loop that will print out the numbers from 1 - 100

If the number is divisible by 3 print `fizz`

If the number is divisible by 5 print `buzz`

If the number is divisible by 3 and 5 print `fizz buzz`

### Arrays and Loops and If Statements, Oh My!

```js
const nums = [1,2,3,4,5,6,7,8,9,10]
```

Write a loop that prints each number in the array

Write another loop that prints every number divisible by 4

Write a final loop that adds every number that is evenly divisible by 4 and then, outside of the loop, console lot the sum

### Arrays of Objects

```js
const solarSystem = [
	{ name: "Mercury", ringSystem: false, moons: [] },
	{ name: "Venus", ringSystem: false, moons: [] },
	{ name: "Earth", ringSystem: false, moons: ["The Moon"] },
	{ name: "Mars", ringSystem: false, moons: ["Phobos", "Deimos"] },
	{ name: "Jupiter", ringSystem: true, moons: ["Europa", "Ganymede", "Io", "Callisto"] },
	{ name: "Saturn", ringSystem: true, moons: ["Titan", "Enceladus", "Rhea", "Mimas"] },
	{ name: "Uranus", ringSystem: true, moons: ["Miranda", "Titania", "Ariel", "Umbriel"] },
	{ name: "Neptune", ringSystem: true, moons: ["Triton", "Nereid"] }
];

```

Iterate through the array and console log the name of each planet

Iterate through the array again and only console log the name of each plant if it does not have a ring system

Iterate through each array again and only console log the arrays if the array is not empty

Iterate through each array agian, and now, if there are moons inside the moon array console log each one separately



### BONUS

Set a checkerboard size to a variable

const boardSize = 8;

Now, using what you know about control flow, build a checkerboard
```
 # # # #
# # # #
 # # # #
# # # #
```
You should be able to change the variable boardSize and generate a larger or smaller grid

const boardSize = 20;

Should now generate:
```js
 # # # # # # # # # #
# # # # # # # # # #
 # # # # # # # # # #
# # # # # # # # # #
 # # # # # # # # # #
# # # # # # # # # #
 # # # # # # # # # #
# # # # # # # # # #
 # # # # # # # # # #
# # # # # # # # # #
```
