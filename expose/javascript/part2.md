1. Console will print out 3, because thats the value of 'var i' after the for loop has run. 
2. It will print out 150. This is because the final value calculated for discountedPrice, in the third iteration of the for loop, is calculated using the last item in the prices array, 300. So, 300*(1-0.5) = 150.
3. The console prints out 150. As previously stated 'var finalPrice' will store the same value as 'var discountedPrice' after the for loop is finished running. That value is 150.
4. The function will return an array, [50,100,150]. These were the values pushed into the array 'discounted' after the calculations in the for loop, then at the end discounted is returned. 
5. This line will throw an error because 'i' is not defined outside the scope of the for loop, since 'i' was declared using 'let' inside the for loop.
6. This line will also throw an error because 'discountedPrice' was not defined outside the scope of the for loop, since it was declared using 'let'.
7. The console will print 150 because 'finalPrice' was defined inside the function itself, so it is accessible from anywhere inside the function.
8. The function will return an array, [50,100,150]. The array, 'discounted' was defined inside the function, so the return call can access the array. 
9. This line will throw an error because 'i' is not defined outside the scope of the for loop.
10. The console prints out 3, because 'length' contains the number pertaining to how many elements are in the array 'prices'.
11. The function will return an array, [50,100,150]. Even through the array 'discounted' is defined as a constant variable, this just means the variable can't be reassigned, but it is still possible to manipulate the elements of the variable.
12. a. student.name 
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. a. 32. The integers are mapped to strings using '+'.
    b. 1. Due to the '-' opertation, the arithmetic is mapped to integers, and normal subtraction is done.
    c. 3. null is treated as 0 since 3 is an integer.
    d. 3null. null is treated as a string since 3 is a string.
    e. 4. "true" maps to 1 as its integer equivalent. So we treat it as 1 + 3.
    f. 0. "false" and "null" are treated as 0, so the equivalent statement is 0+0
    g. 3undefined. "undefined" is trated as string since 3 is a string.
    h. NaN. Since it is a '-' operation, we use the Numeric Conversion for "undefined", which is NaN.
14. a. true. The character '2' becomes integer 2.
    b. false. The character '2' is greater than the first character '1'.
    c. true. The character '2' becomes integer '2'/
    d. false. types are different.
    e. false. True casts to the number 1.
    f. true. All values except 0, null, "" and undefined are casted to "true" in Boolean conversion.
15. == checks for equality with type conversion, whereas === checks for equality without type conversion. 
17. The result is newArr containing, [2,4,6]. Essentially, modifyArray() takes an array and a function, then applies the function to each element of the array, then pushes the new valeus into newArr. In this case, the function doSomething() simply multiplies each element in the input array by 2.
19. 1
    4
    3
    2