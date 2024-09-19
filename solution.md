## Return Negative

```js
const num = 1
function makeNegative(num){
  console.log(num * -1)
} if (num <= 0){
  console.log(num)
}
    
    
  makeNegative(1)
```

## Sum of Positive

```js
const numbers = [1,-4,7,12] 
console.log(numbers[0] + numbers[2] + numbers[3])
```

## Function 2

```js
function numberRoot(num1){
    console.log(Math.sqrt(num1))
}

numberRoot(81)
```

## Sum Arrays

```js
const array = [1 ,2, -10, 16, 21]
let num = 0
  for(let i = 0; i <array.length; i++) {
      num = num + array[i]
  }
  console.log(num)
```

## Reversed Strings

```js
const string = "Worl"
let reverse = "d"
for (let i = string.length -1; i >=0; i--){
    reverse = reverse + string[i]
 }
console.log(reverse)
```
