会从birthday problem出发记录一些感兴趣的其它概率问题。

## birthday problem



| indicator | event                                       |
| --------- | ------------------------------------------- |
| I~ij~     | Individuals *i*, *j* have the same birthday |
|           | NOT independent                             |
| W         | the number of similar pairs                 |
|           | Equals $$\sum_{i<j}I_{ij}$$                 |
|           |                                             |



在这个文档中我暂时设定的一些词（

* **date-based twins**: two people sharing a birthday
* **date-based triplets**: three people sharing a birthday





**canonical birthday problem**

What is the probability of finding $$2$$ people sharing a birthday in a set of $$n$$ randomly chosen people.



​	**I.** What is the probability of finding $$2$$ people with birthdays within $$k$$ calendar days in a set of $$n$$ randomly chosen people.





​	**II.** Interviewing people one by one until finding a <u>date-based twins</u>, how many should be interviewed.





​	**III.** What is the probability of finding at least two pairs (following some rules) such that the ***person1***s in each pair share a birthday and the ***person2***s in each pair share another birthday. 





​	**IV:** What is the probability of finding $$k \ \ (1 ≤ k ≤ \lfloor\frac{n}{2}\rfloor)$$ pairs of <u>date-based twins</u> in a set of $$n$$ randomly chosen people / What is the probability of finding at least one <u>date-based triplets</u>.





**strong birthday problem**

What is the probability in a group of $$n$$ people that everyone in the group shares birthday with someone else in the group.





**也不确定会不会解系列**

What is the probability of finding at least $$k$$ people sharing a birthday with each other in a set of $$n$$ randomly chosen people.





**Theorem**

* Let $$m$$ be the number of equally likely birthdays, $$n$$ be the number of people. 
  $$
  If \ \ m, n \rightarrow \infty \ \ in \ \ such \ \ a \ \ way \ \ that \ \ 
  \frac{n(n-1)}{m} \rightarrow 2\lambda, \\
  then \ \ W \xRightarrow{\mathscr{L}}Poi(\lambda).
  $$
  我知道我证不来系列之一.

*   
  $$
  Suppose \ \ m, n \rightarrow \infty in \ \ such \ \ a \ \ way \ \ that\ \  \frac{n(n-1)}{m} \rightarrow 2\lambda, \\
  then,
  $$
  





### Reference



