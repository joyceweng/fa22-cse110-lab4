# Part 2

1. It will print `3`. Since var is function scoped that can be accessed anywhere inside the function and `prices.length` is 3, we can know that the for loop will run 3 times. In the end `i` will be 3.
2. It will print `150`. Here, `discountedPrice` is a var that can be accessed anywhere inside the function. From `var discountedPrice = prices[i] * (1 - discount);` we can know that 300*(1-0.5)=150.
3. It will print `150`. Here, discountedPrice is a var that can be accessed anywhere inside the function. From`finalPrice = Math.round(discountedPrice * 100) / 100;` we can know that `finalPrice` is 150.
4. The function wil return `[50, 100, 150]`. According to `discounted.push(finalPrice);` we know that the `finalPrice` is pushed to `discounted` each time.
5. It will have an `ReferenceError`. `i` can only be accessed within the block, not outside of the for-loop.
6. It will have an `ReferenceError`. `discountedPrice` can only be accessed within the block, not outside of the for-loop. 
7. It will print `150`. This is because `let finalPrice = 0;` and `finalPrice` are in the same block, so it will printed. Each time in the for-loop it will get a `finalPrice` from `finalPrice = Math.round(discountedPrice * 100) / 100;`.
8. It will return `[50, 100, 150]`. We know that `return discounted;` is in the same block as `let discounted = [];`. In the for-loop the `finalPrice` is pushed into `discounted` each time.
9. It will return a `ReferenceError` because we cannot access `i` after the for-loop.
10. It will print `3` because from `const length = prices.length;` we can know that `length` is 3.
11. It will return `[50, 100, 150]`. Although `discounted` is a const variable that cannot be reassigned, but from `discounted.push(discountedPrice);` we can know that this pushes `discountedPrice` into the array.
12. A. student.name \
    B. student['Grad Year'] \
    C. student.greeting() \
    D. student['Favorite Teacher'].name \
    E. student.courseLoad[0]
13. A. `32` since integers map to their exact string representation. \
    B. `1` since `3` is converted to integer and subtracts. \
    C. `3` since `null` is converted to integer `0`. \
    D. `3null` since `null` is converted to string so that strings are concatenated. \
    E. `4` since true maps to `1`. \
    F. `0` because both `false` and `null` maps to `0`. \
    G. `3undefined` since `undefined` is converted to string so that strings are concatenated. \
    H. `NaN` since `undefined` cannot be converted to an integer.
14. A. `true` as `2` is convereted to an integer.
    B. `false` because both `2` and `12` are converted to an integer. \
    C. `true` because they will compare both `2` as an integer. \
    D. `false` because it doesn't have type conversion. \
    E. `false` because `1` is not equal to `2`. \
    F. `true` because `Boolean(2)` returns true, so they are equal.
15. `===` follows strictly equality comparison algorithm (data type of the operand is important). Where `==` loosely compares two values (data type of the operand isn't important).
16. in a JS file part2-question16.js
17. The result will be `[2, 4, 6]`. `array.length` is 3. And from `callback(array[i]);` we can know that we will get `1*2, 2*2, 3*2` when it loops through. So `2, 4, 6` is pushed into that array `newArr`.
18. in a JS file - part2-question18.js
19. `1` \
    `4` \
    `3` \
    `2`
