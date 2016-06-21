### stringtools
some tools for your string.prototype
###INSTALLATION  
```bash  
npm install stringtools  
```

###Function  
####The two booleans  
In each function:  
    the first is the case sensitive booleans.  
    the second is the accent booleans.  

####searchEquality:  
Ask for a keyword and two booleans.  
The keyword will be compared to the string and return true if they're equal, and return false if they're not. 

####allIndicesOf
Ask for a keyword and two booleans.  
The keyword will be compared to the string and if the keyword match with the string, it will push the indice in an array.
Then it return the array of indices.    

####searchpart
Ask for a keword and two booleans and a char(int)
The keyword will be compared to the string and if the keyword match with the string, it will push the indice in an array.
Then it will restart the operations for char times, and delete the last character of the word for each loop.
return an array.  
