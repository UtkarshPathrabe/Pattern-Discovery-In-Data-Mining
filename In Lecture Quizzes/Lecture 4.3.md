Quiz
====  

Question
--------  

DBLP is a computer science bibliography database. Suppose we want to study the correlation between authors Jure Leskovec (JL) and Hector Garcia-Molina (HG) based on their co-authorship, which is shown in the table.  
Which of the following measures might be appropriate? Check all that apply.  
![Contingency Table](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/In%20Lecture%20Quizzes/Lecture%204.3.png "Contingency Table")  

### Answer  
* Cosine  
* Kulcyzynski  
* AllConf  

### Explanation  
* Since both JL and HG have published hundreds of papers and they have only co-authored one paper, JL and HG are negatively correlated. we have Lift(JL, HG) = 46.87 which is large due to a large number of null transactions. Therefore, Lift is not appropriate in this case and we should use measures that are null-invariant.  
* Since both JL and HG have published hundreds of papers and they have only co-authored one paper, JL and HG are negatively correlated. we have Psi Square(JL, HG) = 44.79 which is large due to a large number of null transactions. Therefore, Psi Square is not appropriate in this case and we should use measures that are null-invariant.  
* Since both JL and HG have published hundreds of papers and they have only co-authored one paper, JL and HG are negatively correlated. We have Cosine(JL, HG) = 4.1e-3 which is small and agrees with our observation.  
* Since both JL and HG have published hundreds of papers and they have only co-authored one paper, JL and HG are negatively correlated. We have Cosine(JL, HG) = 4.1e-3 which is small and agrees with our observation.  
* Since both JL and HG have published hundreds of papers and they have only co-authored one paper, JL and HG are negatively correlated. We have Allconf(JL, HG) = 2.3e-3 which is small and agrees with our observation.  
