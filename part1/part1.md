Answers to Lab 4 Part 1 Questions

1. The console logs the number of items in prices. i is at the size of prices.length.
2. The console logs the unrounded discounted price of the last item from prices. discountedPrice exists at a global scope and is still the last value that was calculated in the last for loop iteration in line 6.
3. The console logs the rounded discounted price of the last item from prices. lastPrice exists at a global scope and is still the last value it pushed to discountedPrices.
4. discountPrices([100,200,300],5) returns 3, 150, 150. This is the size of the list passed in and the last discounted price in the list.

5. The console logs the number of items in prices. i is at the size of prices.length.
6. There is a ReferenceError because discountedPrice only exists in the scope of the for loop, so we cannot log its value outside of the for loop.
7.  The console logs the rounded discounted price of the last item from prices. lastPrice exists at a global scope and is still the last value it pushed to discountedPrices.
8. The function will print 3 to the console then return a ReferenceError.

9. The function will not reach line 11 because there is a TypeError. finalPrice is a const and cannot be reassigned.
10. The function will not reach line 12 because there is a TypeError. finalPrice is a const and cannot be reassigned.
11. The function will not reach line 13 because there is a TypeError. finalPrice is a const and cannot be reassigned.
12. The function will not run because there is a TypeError. finalPrice is a const and cannot be reassigned.

13.
A. student.name  
B. student["Grad Year"]  
C. student.greeting()  
D. student["Favorite Teacher"]["name"]  
E. student.courseLoad[0]  

14. 
A. 32, 2 was typecasted to a string  
B. 1, 3 was typecasted into an integer  
C. 3, null was treated like a 0  
D. 3null, null was treated like a string  
E. 4, true was treated like an integer 1  
F. 0, false was treated like a logical 0 and null was treated like a 0  
G. 3undefined, undefined was treated like a string  
H. NaN, JS attempted to convert undefined into a number but was unable to  

15.
A. true, 2 is treated like an integer  
B. false, both 2 and 12 are treated like integers  
C. true, the second 2 is treated like an integer  
D. false, === checks equality without type conversion  
E. false, true is treated like a number 1  
F. true, any Boolean value that is nonzero is true  
  
16. The == operator will do type conversions if the operands are of different types when checking for inequalities.  
The === operator will not do type conversions and will return false for any different types. 

17 "How are you?" is printed to the console log. This is because 2 == true evaluates to false since the true value is casted to a 1, and 2 == 1 is false. The else if (2) evaluates to true because 2 is a nonzero value and is treated as a Boolean expression, and all Boolean expressions with nonzero values are true.

19 The function will return an array [6,8,10]. This happens because doSomething will run for each element in the list first, adding 2 to each number, then modifyArray will multiply each value in the array by 2.  

21  1 4 3 2
