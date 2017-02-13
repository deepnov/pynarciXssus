# PyXSSParser for XSS detection

This parser attaches few methods and variables to the existing JS Parser to trace any data flow from XSS source property or function to any variable or function with global access.

To summarize, the parser detects the below cases:

A. XSS source assigned to a global variable or global property

B. XSS source assigned to a function return value (exit point)

C. XSS source passed to a function (entry point)



