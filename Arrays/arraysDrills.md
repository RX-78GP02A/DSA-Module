### 1. Implement an Array class from scratch.
Walk through each step of implementing an array. Don't rush through this by copying and pasting the code samples. After you've walked through it and you understand the code of the Array class, *hide the sample code and try writing the Array class from scratch* using the memory module here for allocating memory.

**Be sure to export the memory module and then import it using require.**

### 2. Explore the push() method
Using the Array class you just created above, add an item to the array. Use the following function:
```js
function main(){

    Array.SIZE_RATIO = 3;

    // Create an instance of the Array class
    let arr = new Array();

    // Add an item to the array
    arr.push(3);

    console.log(arr);
}
```
* What is the length, capacity and memory address of your array?

* Add the following in the main function and then print the array:
```js
    ...
    arr.push(5);
    arr.push(15);
    arr.push(19);
    arr.push(45);
    arr.push(10);
```
* What is the length, capacity and memory address of your array? Explain the result of your program after adding the new lines of code.