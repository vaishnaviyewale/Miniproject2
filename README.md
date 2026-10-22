A palindrome is a word, phrase, or sequence that reads the same backward as forward. This project 
implements a palindrome checker using two fundamental data structures: a stack (Last-In, First
Out) and a queue (First-In, First-Out).  

The core logic involves processing an input string by simultaneously pushing each character onto 
a stack and enqueuing it into a queue. To verify if the string is a palindrome, characters are 
subsequently popped from the stack (which returns them in reverse order) and dequeued from the 
queue (which returns them in their original order). 

 If the characters match at every step until both structures are empty, the string is confirmed as a 
palindrome. This project demonstrates the practical application of stacks and queues, highlighting 
their contrasting data handling mechanisms (LIFO vs. FIFO) to solve a classic computer 
science problem.
