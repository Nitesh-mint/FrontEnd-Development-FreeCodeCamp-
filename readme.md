# JavaScript and Css(FreeCodeCamp)
Learning javascript and css from a youtube video of FreeCodeCamp.  
[Course Link](https://www.youtube.com/watch?v=zJSY8tbf_ys&t=4442s) 

## Day 1
Learned about differences between `let`, `var`, `const` 

## Day 2
Learned about different datatypes  like `string` `arrays` `objects` etc


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
// it gives output without instantly
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

Solved one itermediate problem from codewars!