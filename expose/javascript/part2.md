
1. line 12 prints "3". i is defined in the scope since it is declared as a var. i stops iterating at 3 since 3 is the size of the prices list.
2. line 13 prints "150". discountedPrice is defined in the scope since it is declared as a var. discountedPrice will hold the discounted price of the final price in the list which is 300. The discount is 50% off, so discountedPrice will be 150.
3. line 14 prints "150". finalPrice will hold the final price of the last price. The last price is 300 with a 50% discount so it will be 150. 
4. The function returns the array [50, 100, 150]. the discounted var holds the discounted prices. The original prices were [100, 200, 300]. With a 50% discount, those values will become [50, 100, 150].
5. There will be an error since the variable i is only defined in the scope of the for loop.
6. There will be an error since the variable discountedPrice is only defined in the scope of the for loop.
7. line 14 prints "150". finalPrice is defined in the same scope as the print statement. finalPrice will hold the final price of the last price. The last price is 300 with a 50% discount so it will be 150. 
8. The function returns the array [50, 100, 150]. The discounted variable is defined in the same scope as the return statement so it will return the array.
9. There will be an error since the variable i is only defined in the scope of the for loop.
10. Line 12 will print "3" length is defined in the same scope as the print statement and 3 is the length of the prices array.
11. The function returns the array [50, 100, 150]. The discounted variable is defined in the same scope as the return statement so it will return the array.
12. A. student.name  
    B. student['Grad Year']  
    C. student.greeting()  
    D. student['Favorite Teacher'].name  
    E. student.courseload[0]  
13. A. '32', since integers map to their exact string representation when adding string and int.  
    B. 1, since strings map to their int representations if they can be represented as ints when subtracting strings and ints.  
    C. 3, since null maps to 0.  
    D. '3null' since null maps to the string 'null'.  
    E. 4, since true maps to 1.  
    F. 0, since false maps to 0 and null maps to 0.  
    G. '3undefined', since undefined maps to the string 'undefined'.  
    H. NaN, since undefined does not map to any integer value when subtracting undefined from a string.  
14. A. true, when comparing string and int, map the string to its int value, if possible, then compare.  
    B. false, when comparing two strings, use ascii values. '2' is greater than '12' when comparing ascii values.  
    C. true, since '2' is mapped to the int value 2 when using ==.  
    D. false, since '2' is not mapped to anything when using ===. The string '2' is not the int 2.   
    E. false, true maps to 1 when comparing with an int. 1 is not equal to 2.   
    F. true, Boolean(2) evaluates to true   
15. == uses the type conversion that is built into javascript. === does not.   
17. [2,4,6] is returned. the for loop iterates through the array [1,2,3]. Each iteration uses the function that doubles an int and then pushes that new value into the new array. So the result will be an array with values that are double the original array's values. 
19. 1  
    3  
    4  
    2  

 
