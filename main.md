
# JavaScript Arrays, Loops, and If-Else Assignment
## Question 1: Create an Array

### Create an array of 5 numbers. Then, print the array to the console.


```javascript
var nums = [1,2,3,4,5]
console.log(nums)
```

```output
[ 1, 2, 3, 4, 5 ]

```

## Question 2: Access Array Elements

### Given an array var numbers = [10, 20, 30, 40, 50];, print the third and fifth elements from the array.


```javascript
var numbers = [10, 20, 30, 40, 50]
console.log(numbers[2])
console.log(numbers[4])
```

```output
30
50

```

## Question 3: Modify Array Elements

### Given an array var colors = ['red', 'blue', 'green'];, change the second element to 'yellow' and print the updated array.


```javascript
var colors = ['red', 'blue', 'green']
colors[1]="yellow"
console.log(colors)
```

```output
[ 'red', 'yellow', 'green' ]

```

## Question 4: Array Length

### Create an array var animals = ['cat', 'dog', 'elephant'];. Use the .length property to print the total number of elements in the array.


```javascript
var animals = ['cat', 'dog', 'elephant']
console.log(animals.length)
```

```output
3

```

## Question 5: Check if an Element Exists

### Given an array var fruits = ['apple', 'banana', 'cherry'];, write an if-else condition to check if 'orange' exists in the array. Print "Found" if it does, and "Not Found" if it doesn't.


```javascript
var fruits = ['apple', 'banana', 'cherry']
var temp = false
for (var i = 0; i<fruits.length;i++){
    if (fruits[i]==="orange"){
        console.log("Found")
        temp=true
        break
    }
}
if (temp==false){
    console.log("Not Found")
}

```

```output
Not Found

```

## Question 6: Sum of Array Elements

### Write a loop to sum all the elements in the array var numbers = [1, 2, 3, 4, 5]; and print the sum.


```javascript
var numbers = [1, 2, 3, 4, 5]
var temp = 0
for (var i = 0; i<numbers.length;i++){
    temp=temp+numbers[i]
}
console.log(temp)
```

```output
15

```

## Question 7: Find Maximum Element

### Given an array var numbers = [5, 3, 9, 1, 7];, write a program to find and print the maximum element in the array.


```javascript
var numbers = [5, 3, 9, 1, 7]
var temp = numbers[0]
for (var i = 0; i<numbers.length;i++){
    if (numbers[i]>temp){
        temp=numbers[i]
    }
}
console.log(temp)
```

```output
9

```

## Question 8: Find Even Numbers

### Create an array var numbers = [1, 2, 3, 4, 5, 6];. Write a loop to print only the even numbers in the array.


```javascript
var numbers = [1, 2, 3, 4, 5, 6]

for (var i = 0; i<numbers.length;i++){
if ((numbers[i]%2)==0){
    console.log(numbers[i])
}

}
```

```output
2
4
6

```

## Question 9: Count Odd Numbers

### Given the array var numbers = [1, 2, 3, 4, 5, 6, 7, 8];, write a loop to count how many odd numbers are in the array. Print the count.


```javascript
var numbers = [1, 2, 3, 4, 5, 6, 7, 8];
var temp = 0
for (var i = 0; i<numbers.length;i++){
if (!((numbers[i]%2)==0)){
    temp = temp +1
}
}
console.log(temp)
```

```output
4

```

## Question 10: Reverse Array

### Given an array var arr = [1, 2, 3, 4, 5];, write a program to reverse the array and print the reversed version.


```javascript
var arr = [1, 2, 3, 4, 5]
var temp = []
for (var i = arr.length-1; i>=0;i=i-1){
    temp.push(arr[i])
}
console.log(temp)
```

```output
[ 5, 4, 3, 2, 1 ]

```

## Question 11: Find the Index of an Element

### Write a program that checks if the element 'banana' exists in the array var fruits = ['apple', 'banana', 'cherry'];. If it exists, print the index where 'banana' is found.


```javascript
var fruits = ['apple', 'banana', 'cherry']
var temp = false
for (var i = 0; i<fruits.length;i++){
    if (fruits[i]==="banana"){
        console.log(`Found at index ${i}`)
        temp=true
        break
    }
}
if (temp==false){
    console.log("Not Found")
}

```

```output
Found at index 1

```

## Question 12: Remove an Element

### Given an array var colors = ['red', 'blue', 'green', 'yellow'];, write a program to remove the element 'blue' from the array. Print the updated array.


```javascript
var colors = ['red', 'blue', 'green', 'yellow']
colors.splice(colors.indexOf("blue"),1)
console.log(colors)
```

```output
[ 'red', 'green', 'yellow' ]

```

## Question 13: Create an Array of Even Numbers

### Write a program that generates an array of the first 5 even numbers (starting from 0) and prints the array.


```javascript
var nums = []
for (var i = 0; i<=8; i=i+2){
    nums.push(i)
}
console.log(nums)
```

```output
[ 0, 2, 4, 6, 8 ]

```

## Question 14: Check if All Elements are Positive

### Given an array var numbers = [-1, 2, 3, 4, -5];, write an if-else condition to check if all elements are positive. Print "All Positive" if true, otherwise "Not All Positive".


```javascript
var numbers = [-1, 2, 3, 4, -5]
var temp = false
for (var i = 0; i<numbers.length; i++){
    if (numbers[i]<0){
        console.log("Not All Positive")
        temp = true
        break
    }
}
if (temp == false){
    console.log("All Positive")
}

```

```output
Not All Positive

```

## Question 15: Sum of Positive Numbers

### Given an array var numbers = [-1, 2, 3, -4, 5];, write a program to calculate the sum of only the positive numbers in the array and print the result.
```javascript
var numbers = [-1, 2, 3, -4, 5]
var temp = 0
for (var i = 0; i<numbers.length; i++){
    if (numbers[i]>0){
        temp=temp+numbers[i]
    }
}
console.log(temp)

```

```output
10

```
