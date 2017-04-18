# Assignment-21.2


1.Explain the different methods of
● mapper class and
● reducer class
 in brief.
 
 Ans.The three main methods in the mapper class are
 a.set up method
 b.map method
 c.clean up method
 
 setup: Called once at the beginning of the task
We can use hadoop setup method if you want to define user defined parameters to your map task or reducer task and you want to compare the words with mapreduce input file and if you want to use hadoop distributed cache in your mapreduce program at that time we will hadoop setup method.


The three main methods in the reducer class are
a.set up method
b.reduce method
c.clean up method
