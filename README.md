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

Output => 15
```
