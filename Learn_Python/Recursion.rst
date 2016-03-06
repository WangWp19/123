
****************
Recursion course
****************

`recursion <http://www.greenteapress.com/thinkpython/thinkCSpy/html/chap04.html>`_ 

1. the modulus operator turn out to be surprisingly useful.
   
   		- find divisible
   		- extract the right-most digit from a number. %10-the last digit. %100-the last two digits.

2. Remember that = is an assignment operator and == is a comparison operator. Also, there is no such thing as =< or =>.
3. we turn this problem into a smaller problem of same kind.this is called **decomposition**.

::

      the greatest common divisor

Divide and conquer
==================

i. *modular abstractions,isolating*, not only save just a piece of code , but to save much more time and energy.
     	
     	- samll problems are easier to solve than the original one.
     	- **the solutions to small problems can easily be combined to solve the biger problem.**

ii. Recursion is a way to describe problems and way of to design solutions.
     
Tower of Hanoi
==============

*tower 3 be the tagert one, let n be the number of disks*

#. if(n==1) ,{move it from tower 1 directly to tower 3}
   
   **otherwise** 

#. move n-1 disks from tower 1 to tower 2,using tower 3 as temporary storage.
#. move n from tower 1 to tower 3
#. move n-1 from tower 2 to tower 3 with tower 1 as temporary storage.  
   

Algorithm
---------

::

		/N = Number of disks  Beg,aux,end are the pegs
		/
		T(N,Beg,Aux,End)
		Begin
			if N = 1 then
				print: Beg -> End
			else 
				Call T(N-1,Beg, End, Aux);
				Call T(1,Beg,Aux,End);
				Call T(N-1,Aux,Beg,End);
			endif
		End

**Assertions are a systematic way to check that the internal state of a program is as the programmer expected.**



i. what is recursion? 

     0) recursion, or 'divide-and-conquer',allow us to define a function that calls itself to solve a problem by checking it into simpler cases
    
ii. what is recursive case?

     0) a recursive case calls the recursive procedure on a simpler cases(usually a part of the input)
        
iii. what is base case?

     0) a base case is necessary in recursion; it determines when the procedure returns a value(or terminate),rather than continuing the recursive process. 
    	


