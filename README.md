# JS-Sorting-Practice
JS211 Sorting Practice

How to Submit:

- [x] Create a new repo called: "JS-Sorting-Practice".
- [x] Get into the practice of working with branches by creating a new branch called "sorting-branch".
- [ ] Complete a code plan.
- [x] Create a new file called `sorting.js`.
- [ ] Copy/paste & complete the code below using the rubric below.
- [ ] Make a pull request against your master branch and submit the URL to it as your assignment.

Rubric:

* Each correct problem (16 pts. per)
* ES6 Syntax (10 pts.)
* Clean pull request (10 pts.)

Strings to Nums:

* Given 1000 digits of PI as strings, return an array of the digits as numbers
- function stringsToNums that takes in an arr
- loop through the arr to .parseInt() each string to a number
- return those numbers in a new array, numsArr

* With the same numbers, find the sum of the even values
- find the even numbers of the numsArr
- if number % 2 === 0, return that number in a new arr, evens
- reduce evens to find the sum, (acc, curr) => acc + curr;
- evens.reduce(sum)

* Find the index of the first value that = 512 when added to it's index (#ATX!!)
- findIndex of value when value + index === 512

Weather:

* using a higher order function, create an array of the unique 'weather_state_name' values of the weather array. (Your function should return the following array ['Light Cloud', 'Heavy Cloud', 'Showers'])

* find the id of the object in weather that has a min_temp of 15.915