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
