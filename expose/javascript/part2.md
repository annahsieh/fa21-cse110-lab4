1. It will print the value of `i`, which is 3. This is because `i` is declared inside the function using `var`, so it is accessible anywhere inside the function. 
2. It will print the value of `discountedPrice`, which is 150. This is because `discountedPrice` is declared inside the function using `var`, so it is accessible anywhere inside the funciton. 
3. It will print the value of `finalPrice`, which is 150. This is because `finalPrice` is declared inside the function using `var`, so it is accessible anywhere inside the funciton. 
4. The function returns `discounted`, which is [50, 100, 150]. This is because `discounted` is declared inside the function using `var`, so it is accessible anywhere inside the function.
5. The code causes an error because `i` is declared using `let`, so it is only accessible inside the `for` loop.
6. The code causes an error because `discountedPrice` is declared using `let`, so it is only accessible inside the `for` loop.
7. It will print `finalPrice` which is 150. This is because line 14 is inside the same block `finalPrice` is declared in, so line 14 can access `finalPrice`.
8. It will return `discounted`, which is [50, 100, 150]. This is because the `return` statement is inside the same block that `discounted` is declared in, so it can access `discounted`. 
9. The code causes an error because `i` is declared using `let`, so it is only accessible inside the `for` loop.
10. It will print the value of `length`, which is 3. This is because line 12 is in the same block that `length` is declared in.
11. It will return the value of `discounted`, which is [50, 100, 150]. This is because line 14 is in the same block that `discounted` is declared in. 
12. A. `student.name`

    B. `student['Grad Year']`
    
    C. `student.greeting()`

    D. `student['Favorite Teacher'].name`

    E. `student.courseLoad[0]`
13. A. '32' because the number 2 gets converted to the string '2' when concatenated with the string '3'

    B. 1 because the string '3' gets converted to the number 3

    C. 3 because null gets converted to the number 0

    D. '3null' because null gets converted to the string 'null' when concatenated with the string '3'

    E. 4 because true gets converted to the number 1

    F. 0 because both false and null get converted to the number 0

    G. '3undefined' because undefined gets converted to the string 'undefined' when concatenated with the string '3'

    H. NaN because '3' gets converted to the number 3 and undefined gets converted to NaN, so 3 - NaN is NaN
14. A. true because '2' gets converted to the number 2

    B. false because '1' comes before '2' in lexicographical order

    C. true because '2' gets converted to the number 2

    D. false because 2 and '2' are of different types

    E. false because true gets converted to the number 1

    F. true because `Boolean(2)` converts the number 2 to true

15.  Both check for equality, but == performs type conversion if needed (when comparing values of different types) while === does not perform type conversion.
    
17) It will return `[2, 4, 6]`. In the `for` loop it calls `callback` which we passed in as `doSomething`, and `doSomething` returns the result of `array[i] * 2`. The `for` loop iterates through all elements of the array, so `newArr` ends up being `[2, 4, 6]` and is returned. 

19. 1  
    4  
    3  
    2
