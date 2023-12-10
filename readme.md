# JavaScript and Css(FreeCodeCamp)
Learning javascript and css from a youtube video of FreeCodeCamp.  
[Course Link](https://www.youtube.com/watch?v=zJSY8tbf_ys&t=4442s) 

## Day 1
Learned about differences between `let`, `var`, `const` 

## Day 2
Learned about different data types  like `string` `arrays` `objects` etc


## Day 3
Learned about operators like other programming language. 

Only difference is that it has an implicit comparator `===`

Another new thing that is learned is that JS has immediately invoked function

**Example of the normal function**
```
//this is normal funciton 
const result = () => {
	return 50;
}
// it doestnot give output instantly
```    

**Example of the immediately invoked function**   
```
// this is the new one 
const result = (() => {
	return 50;
})();
// it gives output without calling it but instantly
``` 

## Day 4
Learned about Loops, conditionals and switch cases
SOlved 10 problems from Codewars

## Day 5
Solved total of 22 problems in CodeWars
Learned about built-in Methods in javascript!
**Some Example of CallBack functions in js**
```
function multiplier(num){ //a random function
	return num * 5;
}

function mainFunction(num, multiplier){ //passing function as a parameter
	return multiplier(num);
}

```
More simply we can use callback function as 
```
function mainFunction(num, function(num){
	return num*5;
})

```
```
function mainFunction(num, (num) =>{
	return num*5;
})

```

```
function mainFunction(num, num =>num*2;)

```

**Real use case of Callback function in array.map method**
```
const myArray = [1, 2, 3, 4, 5];

//function to return something
function myCustomCallBackFunction(item){
	return item * 2;
}

const newArray = myArray.map(myCustomCallBackFunction); // returns newArray with the doubled value of the original array

```

## Day 6

Learned about String and Date objects in Javascript! Learned about different date methods to work with it.


## Day 7

Learned about basics of RegEx, String Methods and some Array methods 

## Day 8

Solved one intermediate problem from CodeWars!

## Day 9
Learned about DOM like : selecting tag elements, Node Methods etc (just some references!)

## -------------------------------------------------------------------------------------------------------

## CSS starting 
30 minutes of daily css from a youtube video of FreeCodeCamp
[Course Link](https://youtu.be/1Rs2ND1ryYc?si=OwTQzddH30kDSTKm)

### Day 1
Basics of css starting with selectors `id`, `class`, `tag` etc.

### Day 2

The selector with the highest precedence is `id`, second is `class` and the lowest is the lowest is `tag`. **Note**: `inline` is the highest which overrides all the selectors.

Learned some selectors like `hover` `>` `~` etc.

### Day 3

Learned colors and using color picker to match the color we need for our page!

### Day 4

Learned about the background image and url. How to cover whole background without repeating the image!
rgba() function can also be used to control the opacity eg: `rgba(0,0,0,0.1)` will set the opacity to 10% 0-1(0 - 100%)

Linear-gradients and circular-gradients!

### Day 5

Units are of two types: absolute and relative, absolute is not depended to any other thing like `px , cm , mm`
Relative are like `%` which is depended on something. 
**Example of Relative unit**
```

.calss-selector{
	width: 400px; #absolute unit
	height: 70%  #will only take 70% of the selector size. Which is good for responsive webiste!
}

```