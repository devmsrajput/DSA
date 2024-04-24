# Data structure and Algorithm

### ___Sum of natural numbers from 1 to n___
```javascript

function sumOfNaturalNumbers(num){
    let sum = 0;
    for(let i = 0; i <= num; i++){
        sum += i
    }
    
    return sum

    // or

    return (num*(num+1))/2
}
console.log(sumOfNaturalNumbers(5))

// Output => 15
```

### ___Sum of digits in number___
```javascript

function sumOfDigits(num){
    let sum = 0;
    while(num>0){
        sum += num % 10
        num = Math.floor(num / 10)
    }
    return sum
}

console.log(sumOfDigits(32))

// Output => 5
```
