1. comparing sequences and other types
   
   *note* : 
        - comparing objects of deiffent types is legal
        - a list is always smaller than a string 
        - a string is always smaller than a tuple.
        - Mixed number types are compared according to their numeric values. so 0 equals 0.0, etc.

2. tuples
   		
   		i. divisor += (i,),keep this comma to tell it is a tuple
   		ii. immutable      	    

4. lists
   		
      i. mutable.
      ii. append is a **method**,method very important in pythod. [1]_  
      iii. assignment has to do with th binding of names to objects.Mutation has to do with changing the value of objets. 
      iv. SO OK 


6. dictionary
      
      i. a dictionary differs from a list in two ways.
                - one the elements are not ordered.
                - the indecies need not to be integers.
                - and they are not called dicts,the **keys**
                - keys can be any immtable type.  
      
      ii. the key must be immutable, the python use a very clever technique called hashing which would not work if the keys were mutable.    
      
                
      
















.. [1] append(L,e) but is L.append(e),not equivalent to assigning somrthing to L,THIS actually mutates the list. a side effect of the modification it performs on the list.