# variables and Datatypes:
# variables
  - It is used for storing a value in memory or its said by Reserved memory location to store values
   # datatypes
   - defining what type of data is ex: character,integer,float(decimalpoint),boolean
   - char 	1byte 	-127 to 127 or 0 to 255
   - int 	4bytes 	-2147483648 to 2147483647
   - float 4bytes 	+/- 3.4e +/- 38 (~7 digits)
   - double 8bytes 	+/- 1.7e +/- 308 (~15 digits)
   - string 4bytes
   # typedef Declaration
   - it is like defining a new name for existing type
   
   
   # example
   - typedef type newname; 
   - typedef int feet;
   - feet distance;
   - in above example we are having integer as feet and in second we are making integer as feet and defining new name as distance
   
   
   # enumeraated data type
   - enum enum-name { list of names } var-list;
   - enum color { red, green, blue } c;
    - c = blue;
    
    
    
    # example
    - int num;
    - num = 25;
    - int datatype; num = variable name
    
  - // operating with variables

- `#include<iostream>`
- `using namespace std;`

- `int main ()`
- `{
  // declaring variables:
-  ` int a, b;`
-  ` int result;`

  // process:
- `a = 5;`
-  `b = 2;`
 -  `a = a + 1;`
-  `result = a - b;`

  // print out the result:
 - `cout << result;`

  // terminate the program:
- ` return 0;`
}
