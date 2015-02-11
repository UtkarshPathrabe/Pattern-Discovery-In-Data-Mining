Quiz
====  

Question
--------  
Given the FP-tree, and min_sup = 2, which of following itemsets are frequent? Check all that apply.  
![alt text](https://github.com/UtkarshPathrabe/Computer-Programming-BITS-Pilani/blob/master/Weekly%20Quizzes/Quiz0202.png "Mask")  

### Answer  
* {b, c}  
* {c, p}  
* {f, b}  

### Explanation  
We can count the supports from the FP-tree. sup({b, c}) = 2, sup({b, p}) = 1, sup({c, p}) = 3, sup({f, b}) = 2, sup({f, b, m}) = 1. Therefore, given min_sup = 2, {b, c}, {c, p}, and {f, b} are frequent.  
