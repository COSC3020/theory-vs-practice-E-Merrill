# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

### Answer

  One reason is that there can be other factors that can affect runtime, such as 
  other background processes on one's computer (open internet tabs, background downloads/uploads, etc.)
    A second reason is that 


  
- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

### Answer

  Taking into account the asymptotic complexity of a search within a binary tree,
  I would expect the timing to theoretically be slightly higher than around 13 seconds.
  This is because the asymptotic complexity of the search function within a binary search
  tree, on average, is $log_2 n$, which, with an input size of 10,000, comes out to
  roughly be 13.3. The actual timing could be faster or slower depending on other factors.
  
- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

### Answer

  In the case of a binary search tree, what could have potentially happened is that the tree was
  very unbalanced when all of the inserts were completed. This lack of balancing of the tree would noticably slow down
  the actual runtime. In this particular case, it is likely that there are parts of the tree that behave closer to linked lists
  than trees.
  Another cause for this larger than expected runtime would be



I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
