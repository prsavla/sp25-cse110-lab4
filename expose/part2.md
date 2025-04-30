# Answers to Lab 4, Part 2 

1. At Line 12, since var has function scope, console.log(i) will print 3, which is the last value that i is. 
2. 150, the last discounted price
3. finalPrice is 150, it's declared as a var, so it's available inside the whole function,
it's value will be the last final price which is 150.
4. This code will return [50,100, 150] which is 50% off the original prices. 
5. Since we change the variable definitions to let, trying to print i will result in a ReferenceError, because
let only allows it to be within that scope. 
6. Same reason as #5, reference error, not available within that scope
7. Since finalPrice has the scope of the function, finalPrice will be 150.
8. It returns the correct discountedPrices: [50, 100, 150]
9. Reference error, i is not available within that scope
10. Length = 3, it's not changed at all in the code.
11. It will return the correct discounted prices [50, 100, 150]
12. Functions:
    a. student.name 
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. 
    a. output = '32,' + operator joins the 2 strings together
    b. '3' - 2, JavaScript will convert it to a number and subtract, so = 1
    c. 3, null becomes 0 
    d. 3null, regular string concactenation
    e. true becomes 1, so 1 + 3 = 4
    f. false becomes 0, so 0 + 0 = 0
    g. 3undefined, + operator converts them both into strings
    h. NaN, tries to subtract them, but can't convert undefined, so NaN

14. 
    a. true, 2 is converted to a number, it's greater than 1
    b. false, they are lexicographically compared, 2 is after 1
    c. true, == converts the types into numbers
    d. false, triple = checks value and type
    e. false, true is 1, and 1 != 2
    f. true, boolean(2) = true, so true == true

15. == checks for value, but === checks for equality in value and equality in type

16. Done in separate file

17. [2,4,6], the function doSomething is passed as a callback and it's applied on every value on the array, [1,2,3] * 2 = [2,4,6]

18. done in separate file

19. 1, 4, 3, 2 on new lines 