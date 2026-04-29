# Part 2
1. It will print 3 because that is the value of `i` when the `for` loop ended, and `i` was hoisted.
2. It will print 150 because that is the value of `discountedPrice` in that last iteration of the `for` loop, and `discountedPrice` was hoisted.
3. It will print 150 because that is what `finalPrice` was set to in the last iteration of the `for` loop.
4. This function will return the list `[50, 100, 150]` because each of the final prices were pushed to the `discounted` list, which was finally returned.
5. It will cause an error because `i` doesn't exist in line 12's scope.
6. It will cause an error because `discountedPrice` doesn't exist in line 12's scope.
7. It will print 150 because that is what `finalPrice` was set to in the last iteration of the `for` loop.
8. This function will return the list `[50, 100, 150]` because each of the final prices were pushed to the `discounted` list, which was finally returned.
9. It will cause an error because `i` doesn't exist in line 12's scope.
10. It will print 3 because that is what `length` was set to on line 4.
11. This function will return the list `[50, 100, 150]` because each of the final prices were pushed to the `discounted` list, which was finally returned.
12. 
    A. `student.name`
    B. `student['Grad Year']`
    C. `student.greeting()`
    D. `student['Favorite Teacher'].name`
    E. `student.courseLoad[0]`
13. 
    A. '3' + 2 = '32', 2 converted to string
    B. '3' - 2 = 3, '3' converted to number
    C. 3 + null = 0, null converted to 0
    D. '3' + null = '3null', null converted to string
    E. true + 3 = 4, true converted to 1
    F. false + null = 0, false and null both converted to 0
    G. '3' + undefined = '3undefined', undefined converted to string
    H. '3' - undefined = NaN, undefined converted to NaN
14. 
    A. '2' > 1 = true, '2' converted to number
    B. '2' < '12' = false, '12' comes first lexicographically
    C. 2 == '2' = true, '2' converted to number
    D. 2 === '2' = false, '2' not converted
    E. true == 2 = false, true converted to 1
    F. true === Boolean(2) = true, Boolean(2) returns true
15. `==` performs conversions, but `===` does not, so `===` is stricter.
17. The result will be `[2,4,6]`. `modifyArray` iterates over each element of `array` and calls `callback` on it. In this case, `callback` is `doSomething`, which doubles its input.
19. 1
    4
    3
    2
