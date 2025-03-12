# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

### Answer


  One reason is the capabilites of one's hardware. The CPU in a supercomputer would be able to  
  run programs much faster than the average college student's laptop, despite the programs having the same asymptotic complexity.  
  
  A second reason could be ignoring lower order terms, which will have a noticable effect on lower input sizes, and can make the program behave 'abnormally' when only paying attention to the highest order terms.  
  
  A third reason can be that constants are ignored. Ignoring the constants can have an effect because $log(n)$ is MUCH different from $1,000 * log(n)$, or something similar in nature.   
  
  
- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

### Answer

  The theoretical runtime of the same search tree with 10,000 elements comes out to be roughly 6.667 seconds.  
  My process of computing this result is detailed below:  
  
  Asymptotic complexity of Binary Search Tree -- log_2(n)  
  Trial with 1,000 elements -- 5 seconds  
  $log_2(1,000)\neq 5.$  
  There must be some scalar changing what the end result would be, thus;  
  $xlog_2(1,000) = 5$  
  Solving for x nets:  
  $x\approx 0.5$  
  Using this value for x with 10,000 elements in the tree:  
  $xlog_2(10,000)\thickapprox 6.66667$  
  
  
- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

### Answer

  The noticeably larger runtime could be a result of simply running the program on a different computer that is  
  significantly slower than the intial computer.  
  
   Another cause for this larger than expected runtime could be a cooling system that has somehow had its max    
  fan speed reduced to 30 RPM between runs. The computer, having to do many calculations to search the tree, will  
  suddenly find itself a bit toasty thanks to its less-than-satisfactory fan speed.  
  
  A third reason this could have taken so much longer could be other background processes going on, like listening  
  to a 7 hour long story on YouTube, or playing a game with Ray Tracing and graphics put to the max, or both!  



I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

I got a lot of help coming up with reasons from Aidan Newberry, and he and Noah Vogt also helped me figure out how to go about solving  
the runtime of the program in problem 2.  
