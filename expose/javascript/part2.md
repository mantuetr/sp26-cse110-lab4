1. It will print out 3. Because "i" is the iteration of the for loop. And, 
   i = 0, i < prices.length, which means 100(0), 200(1), 300(2). Then, 
   3 is not < prices.length. so, it will skip the loop and print 3
2. it will print 250. Since, the last input is 300. Do the math will become 150,
   and since it's "var" so it can be access outside the block. Keep the last 
   value of the loop
3. print 150. Since, finalPrice is declared outside the loop so, it will get 
   update every iteration. And, the last iteration is 300, which do the math 
   will be 150
4. [50, 100, 150]. Because each time, they do math, the finalPrice will be 
   pushed to the discounted (declared outside the loop). And, at the end of the 
   for loop, there will be 3 finalPrice get pushed into the "discounted" array
5. Error. Because "i" uses "let" so it is a block scope, so it cannot be used
   outside of the for loop, which will give an error. "i" cannot be defined
6. Error. The same reason as before, because "discountedPrice" is the block 
   scope so it cannot be accessed outside of the block. The code cannot define 
   it.
7. print 150. Since, the variable is declared outside of the for loop. So, it 
   can be accessed. And, same with question 2. It will keep the last value in 
   the loop and print 150
8. [50, 100, 150]. Since, the "discounted" is declared outside the for loop, so
   it can be accessed. at the end of the for loop, there will be 3 finalPrice 
   get pushed into the "discounted" array 
9. Error. Because "i" uses "let" so it is a block scope, so it cannot be used
   outside of the for loop, which will give an error. "i" cannot be defined
10. It will print 3. Since, the "const length = prices.length" will be 3. And,
    "length" does not change value throughout the code so no error, print out 3
11. [50, 100, 150]. Since, it's an empty array, so at the end, when push the
    finalPrice in, it is not reassigning the value but modifying it, so it does
    not cause error
12. a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. a. '32'. Because 2 is converted to string so concatenate two strings 
    together, give '32'
    b. 1. Because "-" is only for numeric as subtract. So, '3' is converted to 
    int, which makes 3 - 2 = 1
    c. 3. because null is 0 in math. So, 3 + 0 = 3
    d. 3null. Since, '3' is a string so null is converted to 'null', and two
    concatenates give "3null"
    e. 4. Because true is 1 in math, so 1 + 3 = 4
    f. 0. Because false and null are both 0 in math, so 0 + 0 = 0
    g. '3undefined'. Since, '3' is a string so null is converted to 'undefined', 
    and two concatenates give "3undefined"
    h. NaN. '3' is converted to 3 and undefiend is NaN in numeric. So, 
    3 - NaN = NaN
14. a. true. Because '2' is converted to int 2 and compare with 1, which is 
    larger, so true
    b. false. Because both are strings, so it compares the first character, 
    which is '2' and '1' and '2' is not smaller than '1', so it's false
    c. true. Because '2' is converted to int 2, and 2 is equal to 2, so true
    d. false. Because === checks VALUE and TYPES. So, int is not equal to string
    which is false
    e. false. Because true is 1 in int. And, 1 is not same as 2, so false
    f. true. Because Boolean(2) is true for boolean, any non-zero number is 
    true. so, true === true is true
15. === checks VALUE and TYPES. So, if they have different types, it cannot
    compare together. == can convert the types to coompare to each other
16. [question16](part2-question16.js)
17. [2, 4, 6]. The code calls modifyArray([1, 2, 3] doSomething). So, the 
    modifyArray will pass the array [1, 2, 3] in, and it will go through the for
    loop, for index 0, which is 1, it will be pushed to the newArr after
    going through the callback function, which is doSomething. So, it will be
    doSomething(1), return 2, 1 * 2 = 2. Then, 2 will be the result and push to
    the newArr. Then, continue with 2, and 3, the results will be 4, and 6.
    Then, i < array.length(3). It will stop and print out the newArr has the 
    result of doSomething, is [2, 4, 6].
18. [question18](part2-question18.js)
19. 1, 4, 3, 2. Print 1, 4 immediately. Then, 3 even though it is with 0, run 
    after all synchronous code finishes. Then 4, because print it after 1 second
