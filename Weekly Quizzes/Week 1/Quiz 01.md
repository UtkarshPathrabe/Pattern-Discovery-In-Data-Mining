Quiz 01
=======  

Question 01
-----------  
Which of the following tasks does not fall under the scope of data mining? Select all that apply.  

### Answer  
* Data Cleaning.  
* Data entry.  

Question 02
-----------  
|Tid|    <b>Items bought</b>         |
|:-:|:------------------------------:|
| 10|              Beer, Nuts, Diaper|
| 20|      Beer, Coffee, Diaper, Nuts|
| 30|              Beer, Diaper, Eggs|
| 40|          Beer, Nuts, Eggs, Milk|
| 50|Nuts, Coffee, Diaper, Eggs, Milk|  
Table 1: Transactions from a database.  

Given the transaction in Table 1 and minsup s = 50%, how many frequent 3-itemsets are there?  

### Answer  
0  

### Explanation  
There are no frequent 3-itemsets by the minsup criterion alone.  

Question 03
-----------  
|Tid|    <b>Items bought</b>         |
|:-:|:------------------------------:|
| 10|              Beer, Nuts, Diaper|
| 20|      Beer, Coffee, Diaper, Nuts|
| 30|              Beer, Diaper, Eggs|
| 40|          Beer, Nuts, Eggs, Milk|
| 50|Nuts, Coffee, Diaper, Eggs, Milk|  
Table 1: Transactions from a database.  

A strong association rule satisfies both the minsup and minconf thresholds. Given the transactions in Table 1, minsup s = 50%, and minconf c = 50%, how many strong association rules are there? Note that the association rule A => B and B => A are distinct.  

### Answer  
6  

### Explanation  
*Frequent itemsets: minsup = 50%  
1. Freq. 1-itemsets: Beer: 4, Nuts: 4, Diaper: 4, Eggs: 3  
2. Freq. 2-itemsets: {Beer, Diaper}: 3
* Association rules: minconf = 50%  
1. Beer => Diaper (60%, 75%)  
2. Diaper => Beer (60%, 75%)  
3. Beer => Nuts (60%, 75%)  
4. Nuts => Beer (60%, 75%)  
5. Diaper => Nuts (60%, 75%)  
6. Nuts => Diaper (60%, 75%)  

Question 04
-----------  
|Tid|    <b>Items bought</b>         |
|:-:|:------------------------------:|
| 10|              Beer, Nuts, Diaper|
| 20|      Beer, Coffee, Diaper, Nuts|
| 30|              Beer, Diaper, Eggs|
| 40|          Beer, Nuts, Eggs, Milk|
| 50|Nuts, Coffee, Diaper, Eggs, Milk|  
Table 1: Transactions from a database.  

Given the transactions in Table 1, minsup s = 50%, and minconf c = 50%, which of the following is an association rule? Select all that apply.  

### Answer  
* Beer => Nuts  
* Nuts => Diaper  

### Explanation  
*Frequent itemsets: minsup = 50%  
1. Freq. 1-itemsets: Beer: 4, Nuts: 4, Diaper: 4, Eggs: 3  
2. Freq. 2-itemsets: {Beer, Diaper}: 3
* Association rules: minconf = 50%  
1. Beer => Diaper (60%, 75%)  
2. Diaper => Beer (60%, 75%)  
3. Beer => Nuts (60%, 75%)  
4. Nuts => Beer (60%, 75%)  
5. Diaper => Nuts (60%, 75%)  
6. Nuts => Diaper (60%, 75%)  