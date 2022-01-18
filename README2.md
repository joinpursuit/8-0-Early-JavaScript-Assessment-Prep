# Drills Part 2

## Try My Luck

- Create a variable called `flip`
- Create an if/else statement that 
   if flip is greater than .5 log `heads`
   if flip is less than .5 log `tails`
 - Assign different values to `flip` to test that yoru if/else statment works


- Write a function `coinFlip` 
   - move your code for your if/else into the function
   - call/invoke your fucntion 

- Instead of hard-coding a value for `flip`, use `Math.random()` to assign a new value every time `coinFlip` is called

- Edge case: what if `flip` is exactly .5? Upgrade your code to handle this, have the message read `The coin landed perfectly on its edge`

- Write a loop that calls `coinFlip` 10 times

## If Dogs Could Talk


```js

const dogTalk = ['why are cats so mean?', 'did someone say go for a walk?!', 'hi! hi! hi! hi!', 'life is good!', "I swear I don't know who ate your shoe!", 'oh yeah, I could eat!'] 

```
- Write a for loop that console logs everything the dog says
- Write another for loop that console logs every other thing the dog says
- Write a loop that runs 20 times
 - Inside that loop, use `Math.random()` to print a number between 0 and 5
 - Upgrade this loop that instead of printing a number, it prints one of the dog's statements randomly (based on array index)
 - Upgrade this loop that every odd time it console.logs `woof`, otherwise it logs the random statement

- Write a for of loop that console logs everything the dog says

## Meal Planner

- Create an array of 7 objects called `myMeals`
- Each objet will have the following keys
 - day (Monday, Tuesday, Wedesday...)
 - meal (soup, oatmeal, fried ice cream...)
 - isHealthy (true, false)
 - calories (an integer between 10 - 10_0000)

```js
const myMeals = [
  {
    day: "Sunday",
    meal: "Tofurkey Pannini with bacon-like peas and chocolate sauce",
    isHealthy: "false",
    calories: 2_200
  },
  // add at least 6 more
]
```
- Test your code, make sure your array of objects is free of syntax errors before moving on

- Write a function `mealPlanner` that takes in a parameter called `meals`
- Have this function console log all the meals
  - Make sure your console log is logging `meals` and not `myMeals` - Why? Write your answer as commented out code. Trying to put your thoughts into words helps you solidify your understanding.
  - Add another parameter called `healthy`
   - When the second argument being passed is true, log only the healthy foods
   - If the second argument being passed is false, log only the unhealthy foods
   - console log only the meal

- Write a function called `todaysMenu`, that takes the parameters called `meals` and `day`
- Pass in `myMeals` and the day of the week
- It should return the meal for that day
- Add a comment in your code that explains the difference between console logging something and returning something
 - Challenge! If there is more than one meal for that day, return an array of all the meals for that day

- Write a new function `calorieCounter` that takes in a parameter called `meals`
- Have this function sum up all the calories in all your meals and `return` them
- Instead of returning the calorie amount change it to be
 - if the value is over 20,0000 calories a week return the value and a "this calorie count seems  high"
 - if the value is below 14,000 calories a week return the value and a "this calorie count seems low"
 - if the value is between 20,000 and 14,000 calories return "this seems like a reasonable amount of calories"

So if the calorie amount is 16,432. It would return

`16,432: this seems like a reasonable amount of calories`


