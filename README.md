fibonacci-generator-recursive

Function recursiveFib, that generates a fibonacci sequence, with a solution implemented recursively. 

Two parameter inputs: 

i) sequence = array comprising two numbers forming beginning of sequence; and 
ii) length = length of the output array. 

Base case checks that sequence is not greater than or equal to length (len). If sequence >= len, return sequence.

If sequence is not >= len, then push last two array values to the sequence array, and then add new sequence as input parameter 
when calling the recursiveFib function from inside the function (i.e. recursively). 

Solution implemented using ES6 arrow notation.
