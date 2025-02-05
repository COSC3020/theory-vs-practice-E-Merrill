# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.
    One reason is that there can be other factors that can affect runtime, such as other background processes on one's computer (open internet tabs, background downloads/uploads, etc.)
    A second reason is

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

    Taking into account the asymptotic complexity of a search within a binary tree,
    I would expect the timing to theoretically be slightly higher than around 13 seconds.
    This is because the asymptotic complexity of the search function within a binary search tree
    is $'log_2 n'$

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

Add your answers to this markdown file.
