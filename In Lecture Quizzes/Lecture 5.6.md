Quiz
====  

Question
--------  
Which of the following statements about the Pattern-Fusion algorithm are FALSE? Check all that apply.  
* The initial pool contains a small set of large patterns.  
* At each iteration, we fuse together a set of small patterns to generate a set of super-patterns.  
* The patterns fused together in each iteration are always from the candidate pool at the beginning of each iteration.  
* The candidate pool for iteration i+1 are the resulting super-patterns of iteration i.  
* The algorithm terminates when the maximum size of super patterns reaches a certain threshold.  

### Answers and Explanation:  
* "The initial pool contains a small set of large patterns" is false because the initial pool contains only small patterns.  
* "The patterns fused together in each iteration are always from the candidate pool at the beginning of each iteration" is false because we also include patterns from a small bounding ball around the candidate patterns from the pool.  
* "The algorithm terminates when the maximum size of super patterns reaches a certain threshold" is false because the terminating condition is on the number of super patterns produced, not the size. The number of super patterns produced is inversely correlated with the size, but it is difficult for us to know the upper bound a priori.  