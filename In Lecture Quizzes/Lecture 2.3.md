Quiz
====  

Question
--------  

|<b>Frequent Pattern</b>|<b>Support</b>|
|:---------------------:|:------------:|
|Beer, Nuts, Diaper     |           10 |
|Beer, Coffee, Diaper, Nuts|	20|
|Beer, Diaper, Eggs	|30|
|Beer, Nuts, Eggs, Milk	|40|
|Beer, Nuts, Diaper, Eggs, Milk	|30|  
Which of the frequent patterns in the table is closed pattern but not a max pattern? Check all that apply.  

### Answer  
* {Beer, Nuts, Diaper}  
* {Beer, Nuts, Eggs, Milk}  

### Explanation  
*  {Beer, Coffee, Diaper, Nuts} is a max pattern since there are not any frequent super patterns of it.  
* {Beer, Diaper, Eggs} has a super pattern with the same support, hence it is not a closed pattern.  
* {Beer, Nuts, Diaper, Eggs, Milk} is a max pattern since there are not any frequent super patterns of it.  