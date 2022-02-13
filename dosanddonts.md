## dont
### global variables 
Global variables can be used by everyone, both inside of functions and outside.
Dont use global variables. Preference for local variables inside of a function. They cna be accessed by anything outside of any function. It is better for unit testing also.

### try, except, pass
try, except, pass statements are risky as you can pass and miss an exception that is occurring
Remediate this by removing, making it good practice to not use the pass statement unless really needed as well as enable debug logging for better allowance of stack trace analysis

### unpythonic loops
dont: define an index, init to 0, find length of array, looping, incrementing
do: `for socks in shoes; print (socks);` is good

### not specifying data types
use them! [link](https://www.w3schools.com/python/python_datatypes.asp)

# dos
unittest

snakecase vs camelcase


