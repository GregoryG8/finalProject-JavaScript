## Assignment Instructions

In this exercise, you will work with some data provided as an array of objects, listing information about dishes available in the Little Lemon restaurant.
<br><br>

**Step 1:** In the function `getPrices()`, give it the parameter of `taxBoolean`.

**Step 2:** Inside the `getPrices()` function, code a for loop that will loop over all the objects inside the `dishData` array.

**Step 3:** Inside the for loop, declare a `finalPrice` variable, without assigning it a value.

**Step 4:** Still inside the for loop, add an if condition, checking that the `taxBoolean` is set to `true`. Inside the if block, multiply the following: * the price of the currently looped-over object from the `dishData` array, and * the tax value. Assign the multiplied value to the finalPrice variable.

**Step 5:** Right after the if condition, add an else if, checking if the value of `taxBoolean` is false. Inside this condition's block, assign the currently looped-over dish price property in the `dishData` array to the `finalPrice` variable.
<br><br>

**Step 6:** Code the `else` case, and inside of it, add two lines of code:

A console log of the string:  

- "You need to pass a boolean to the getPrices call!"  

- return (to "jump out" of the further function execution)
<br><br>

<b>Step 7:</b> After all the conditional's statements, but still inside the for loop, code another console log with four arguments:

1. The string `"Dish: "`

2. The value of currently looped-over dish object's name property

3. The string `"Price: $"`

5. The value of the `finalPrice` variable
<br><br>

**Step 8:** You're finshed with the `getPrices()` function, and now you're ready to code another function. Give the `getDiscount()` function, two parameters: the `taxBoolean` and the `guests` parameter. 

**Step 9:** Inside the `getDiscount()` function,  on the very first line of its body, invoke the `getPrices()` function, passing it the `taxBoolean` as an argument.