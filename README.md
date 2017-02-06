# PyXSSParser for XSS detection

PyNarcissus is a standard Javascript parser created by JT Olds in Python. Here it is customized to perform some XSS taint detection. The Original Narcissus parser was written in Javascript by Brendan Eich (Javascript creator). This fork maintains the same structure and approach used in Narcissus, except adding few methods and variables to track taint propagation for any Cross Site Scripting scenario.

The below cases will be covered:

a]XSS source assigned to a global variable

b]XSS source assigned to a function return value

c]XSS source passed to XSS sink function

d]XSS source assigned to XSS sink within function
