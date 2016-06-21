### stringtools
some tools for your string.prototype
###INSTALLATION  
```bash  
npm install stringtools  
```
### Require
in your code, add at the begining of the file
````bash
require('stringtools');
````
###Function  
####The two booleans  
In each function:  
    the first is the case sensitive booleans.  
    the second is the accent booleans.  

####searchEquality(keyword[string],caseSensitive[boolean],latinize[boolean]):  
The keyword will be compared to the string and return true if they're equal, and return false if they're not. 

####allIndicesOf([keyword[string],caseSensitive[boolean],latinize[boolean]):
The keyword will be compared to the string and if the keyword match with the string, it will push the indice in an array.
Then it return the array of indices.    

####searchpart(keyword[string],char[int],caseSensitive[boolean],latinize[boolean])
The keyword will be compared to the string and if the keyword match with the string, it will push the indice in an array.
Then it will restart the operations for char times, and delete the last character of the word for each loop.
return an array.  
Exemple:
````
myString.searchpart("strp",2,true,true);
will be compared :
first loop myString and strp
second loop myString and str
last loop  myString and st
````
