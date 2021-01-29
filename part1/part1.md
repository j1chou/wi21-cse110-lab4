1. At line 11, console.log(i) will print the length of price as i is declared with var, meaning it is visible through code blocks
2. At line 12, console.log(discountedPrice) will print out the last discounted price calculated within the for loop, as it is declared with var and is thus visible 
3. At line 13, console.log(finalPrice) will print out the last finalPrice calculated within the for loop, as it is declared with var and is thus visible 
4. Calling the function with discountPrices([100, 200, 300], .5) will return [50, 100, 150], the discounted array. The array is populated by calculating a discountedPrice by multiplying the discount percentage to items of the price array, rounding the result, then storing it into the discounted array. 

5. At line 11, the error "Uncaught ReferenceError: i is not defined" will be thrown because it is declared in the for loop with let
6. At line 12, the error "Uncaught ReferenceError: discountedPrice is not defined" will be thrown because it is declared in the for loop with let
7. At line 13, the last finalPrice calculated within the for loop will be printed, as it is declared outside of the for loop with let
8. Calling the function with discountPrices([100, 200, 300], .5) will return [50, 100, 150], the discounted array. The array is populated by calculating a discountedPrice by multiplying the discount percentage to items of the price array, rounding the result, then storing it into the discounted array. 

9. At line 11, the error "Uncaught ReferenceError: i is not defined" will be thrown because it is declared in the for loop with let
10. At line 12, the error "Uncaught ReferenceError: discountedPrice is not defined" will be thrown because it is declared in the for loop with let
11. At line 13, 0 will be printed since finalPrice is never updated as it is declared as a const at the beginning of the function.
12. The function will return an 3 item array populated by 0's since the variable finalPrice which gets pushed into the array discounted is declared as const and thus unalterable.

DataTypes:
13. A: student.name
    B: student["Grad Year]
    C: student.greeting()
    D: student["Favorite Teacher"].name
    E: student.courseLoad[1]

Basic Operator & Type Conversion
14.  
A. 32, since '3' is a string, and since the operation is +, 2 got treated as a string 
B. 1, since the operation is -, '3' was treated as a number 
C. 3, since 3 is a number, and the operator is +, null was treated as the number 0
D. 3null, since 3 is a string, the operator + was treated as concatenation
E. 4, with the same reasoning as C, with true being treated as 1.
F. 0, since the operator is + and neither is a string, false and null were treated as numbers to yield 0+0 = 0
G. 3undefined, for the same reason as A.
H. NaN, since the string is treated as a number here, undefined becomes NaN

15. 
A. true, string '2' becomes number 2
B. false, string '2' is larger than string '1'
C. true, value 2 is equal to value 2
D. false, int 2 is not string 2
E. false, true is equivalent to 1, and 1 is not equal to 2
F. true, Boolean(2) yields true so true is true

16.
== compares with type conversion, while === compares without type conversion

Conditionals
17. "How are you?" is printed because the first conditional, (2 == true), is false because true is converted to a number, 1, and thus fails 2==1. else if(2) is true since 2 converts to true when undergoing boolean conversion, same as any non-zero value. Since we're in an else if branch, we will not run the last branch. Hence, "How are you?" is printed.


 
