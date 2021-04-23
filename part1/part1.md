# Part 1

## Part 1a
1. Line 9 prints "values added: 20" because the scope of var is global.
2. Line 13 prints "final result: 20" because the scope of var is global.
3. Line 9 prints "values added: 20" because the scope of var is global.
4. There is an error on this line because result is not defined. This is because using let makes it so that it cannot be accessed outside the block it is defined in.
5. There is an error because you cannot assign values to a constant variable.
6. There is an error because the variable is not defined. This is because using const makes it so that it cannot be accessed outside the block it is defined in.

## Part 1b
1. The number 3 will be printed. This is because this the final value which is assigned to i when the for loop is finished.
2. The number 150 will be printed. This is because this is the final value which discountedPrice is assigned when the for loop is finished.
3. The number 150 will be printed. This is because this it he last number that finalPrice is assigned in the for loop.
4. The array [ 50, 100, 150] will be returned. This is because we push the finalPrices into an array called discounted and return that array at the end of the function.
5. There is an error that i is not defined. This is because it is not in the scope of the for loop where it is declared.
6. There is an error that discountedPrice is not defined. This is because it is not in the scope of the for loop where it is declared.
7. The number 150 is printed in the console. This is because the variable is defined before the for loop and so the value is still within the scope of where it is declared.
8. This function will return the array [ 50, 100, 150] because the function is still able to run properly because all values are properly scoped when they need to be calculated.
9. There is an error that i is not defined. This is because it is inot in the scope of the for loop where it is declared.
10. The number 3 was printed. This is because that is the length of the variable length and it is properly defined (scope is correct)
11. The array [ 50, 100, 150] is returned. This is because we push the final prices into the array called discounted and return that array at the end of the function. The variable is also declared prior and is in proper scope.

12. A: student['name']
    B: student['Grad Year']
    C: student.greeting()
    D: student['Favorite Teacher']['name']
    E: student['courseLoad'][0]

13. A: 32
    B: 1
    C: 3
    D: '3null'
    E: 4
    F: 0
    G: 3undefined
    H: NaN

14. A: true
    B: false
    C: true
    D: false
    E: false
    F: true

15. == compares variables but ignores datatypes while === compares variables and checks types

17. The result of the function will be the array [2, 4, 6]. What it does essentially is run through all values inside of the initial array [1, 2, 3], and calls the function doSomeothing on it which returns the input value * 2. In this case, the input value of doSomething would be the values of the array [1, 2, 3] which would be returned and pushed back into a new array which is returned which is why we get [2, 4, 6] (the array [1, 2, 3] with all values multiplied by 2).

19. The output was 1, 4, 3, 2. This is because the 1 was logged first, then the log 4 was run, and then the setTimeout of log 3 was finished waiting 0 milliseconds, and then the setTimeout of the log 2 was finished waiting 1000 milliseconds.