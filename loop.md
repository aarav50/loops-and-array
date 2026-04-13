
# Loops Assignment
## `for` · `while` · `do-while`  ·  single loop variable only
## 15 Questions
## 3 Sections
## Level: Beginner
## Section A — `for` loop (Q1–5)

### 1.Print numbers from 1 to 10. `for`
```javascript
for (var i = 1 ; i<=10; i++){
    console.log(i)
}
```

```output
1
2
3
4
5
6
7
8
9
10

```

### 2.Print numbers from 10 down to 1. `for`

```javascript
for (var i = 10; i>=1; i--){
    console.log(i)
}
```

```output
10
9
8
7
6
5
4
3
2
1

```

### 3.Print all even numbers from 2 to 20. `for`

```javascript
for (var i = 2; i<=20;i=i+2){
    console.log(i)
}
```

```output
2
4
6
8
10
12
14
16
18
20

```

### 4.Print the multiplication table of 5 (5×1 to 5×10). `for`

```javascript
for (var i = 1 ; i<=10; i++){
    console.log(`5*${i} : ${i*5}`)
}
```

```output
5*1 : 5
5*2 : 10
5*3 : 15
5*4 : 20
5*5 : 25
5*6 : 30
5*7 : 35
5*8 : 40
5*9 : 45
5*10 : 50

```

### 5.Print the sum of numbers from 1 to N (take N as input). `for`
```javascript
var n = 0
var temp = 0
for (var i = 1; i<=n; i++){
 temp = i+temp
}
console.log(temp)
```

```output
0

```

## Section B — `while` loop (Q6–10)
### 6.Print numbers from 1 to 10 using a while loop. `while`
```javascript
var i = 1
while (i<=10){
    console.log(i)
    i=i+1
}
```

```output
1
2
3
4
5
6
7
8
9
10

```

### 7.Print all odd numbers between 1 and 20. `while`
```javascript
var i = 1
while (i<=20){
    console.log(i)
    i=i+2
}
```

```output
1
3
5
7
9
11
13
15
17
19

```

### 8.Print powers of 2 starting from 1 until the value exceeds 100. `while`
```javascript
var i = 2
while (i<=100){
    console.log(i)
    i=2*i
}
```

```output
2
4
8
16
32
64

```

### 9.Count how many times you can halve a number N (input) before it becomes less than 1. `while`
```javascript
var n = 0
var c = -1
while (n>=1){
    c=c+1
    n=n/2   
}
if (c == -1){
    console.log(0)    
}
else{
    console.log(c)
}
```

```output
0

```

### 10.Print the first 10 multiples of a number N given by the user. `while`
```javascript
var n = 0
var c = 1
while (c<=10){
    console.log(c*n)
    c=c+1
}

```

```output
0
0
0
0
0
0
0
0
0
0

```

## Section C — `do-while` + patterns (Q11–15)
### 11.Keep asking the user to enter a number. Stop when they enter a negative number. Print each entered number. `do-while`
```javascript
var n = 2
do{
    n = -8
    console.log(n)
}while(n>=0)
```

```output
-8

```

### 12.Print numbers 1 to 5, then print "Done!" after the loop ends. `do-while`
```javascript
var n = 1
do{
    console.log(n)
    n=n+1
}while(n<=5)
console.log("Done!")
```

```output
1
2
3
4
5
Done!

```

### 13.Keep taking number inputs and print their running sum. Stop when the user enters 0. `do-while`
```javascript
var n = 0
var total = 0
do{
 n = 0
 total=total+n
}while(n!=0)
    
```

```output
0
```

### 14.Print a row of N stars on a single line (N given by user). `for`
```javascript
var n = 2
var temp=""
for (var i = 0; i<n;i++){
    temp=temp+"*"
}
console.log(temp)
```

```output
**

```

### 15.Print increasing stars on each line — 1 star on line 1, 2 on line 2, and so on up to N lines. Each line is printed by a single loop. `for`
```javascript
var n = 2
var temp=""
for (var i = 0;i<=n;i++){
    temp=""
    for (var ii = 0; ii<i;ii++){
    temp=temp+"*"
}
console.log(temp)

    
}
```

```output

*
**

```
