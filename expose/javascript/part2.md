1. 3 will be outputted because the for loop iterated over the prices array which has 3 items in it, so i ended up being set to 3.  
2. 150 will be outputted because the last element in the prices array is 300, and discountedPrice is set to 300 * 0.5 = 150 in the last iteration of the for loop.  
3. 150 will be outputted because in the last iteration of the for loop, finalPrice gets the value of discountedPrice in the last iteration as well which is 150, and (150 * 100)/100 = 150.  
4. The function returns [50, 100, 150] because each element in the array is iterated over in the for loop, and with the arithmetic performed, gets pushed into the discounted array.  
5. Error because i cannot be accessed outside of the for loop since it was declared using let inside of the for loop.  
6. Error because discountedPrice cannot be accessed outside of the for loop since it was declared using let inside of the for loop.  
7. 150 will be outputted because in the last iteration of the for loop, finalPrice gets the value of discountedPrice in the last iteration as well which is 150, and (150 * 100)/100 = 150. There's no issue since finalPrice was declared with let outside of the for loop.  
8. The function returns [50, 100, 150] because each element in the array is iterated over in the for loop, and with the arithmetic performed, gets pushed into the discounted array.  
9. Error because i cannot be accessed outside of the for loop since it was declared using let inside of the for loop.  
10. 3 will be outputted because the prices array which has 3 items in it, so console.log(length); outputs 3.  
11. The function returns [50, 100, 150] because each element in the array is iterated over in the for loop, and with the arithmetic performed, gets pushed into the discounted array.
12. A: student.name, B: student['Grad Year'], C: student.greeting(), D. student['Favorite Teacher'].name, E. student.courseLoad[0];  
13. A. '32' because the string '3' is concatenated with the string representation of 2 to make '32', B. 1 because '3' can be converted to the number 3, making the expression 3 - 2 = 1, C. 3 because null is treated as 0, so 3 + 0 = 3, D. 3null because the string '3' is concatenated with the string 'null' to make '3null', E. 4 because true becomes 1, and 1 + 3 = 4, F. 0 because false becomes 0, and null is treated as 0, so 0 + 0 = 0, G. 3undefined because the string '3' is concatenated with the string 'undefined' to make '3undefined', H. NaN because undefined gets converted to NaN when subtracting '3' - undefined, resulting in NaN.
14. A. true because '2' is converted into the number 2, and 2 is greater than 1, B. false because in comparing the strings lexicographically, '2' > '1' in '12', so '2' !< '12', C. true because '2' is converted into the number 2, and 2 = 2, D. false because === checks equality without type conversion, and the number 2 is not equal to the string '2', E. false because true because 1, and 1 is not equal to 2, F. true because Boolean(2) outputs true, and true === true.
15. == will convert the values on both sides to a common type and then check for equality, whereas === strictly checks if the values are equal with the same type.
17.[2,4,6] because each element in the array is passed through the doSomething function which multiplies each element by 2, and then each multiplied element is pushed into the newArr.
19. 1 4 3 2  
