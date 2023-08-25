# CCalculatorProject

Welcome to the C Calculator project! This calculator was developed as a class project to showcase fundamental C language programming concepts. It is designed to perform a variety of simple commands including AND, OR, SUM, UPPER, ARRAYSUM, ListSum, ATOQ, and POPCNT. This README provides an overview of the project, its features, and instructions for usage.

Commands:

AND:
	Returns a signed 8 byte integer that is the bitwise AND of two 8 byte signed integers x and y.

OR:
	Returns a signed 8 byte integer that is the bitwise OR of two 8 byte signed integers x and y.

SUM:
	Updates the global variable SUM_POSITIVE and SUM_NEGATIVE depending on the sign of y.  Returns x + y.

UPPER:
	takes in 1) running result and 2) a pointer to an ascii string. The function upper case’s any lower case characters in the string and returns the addition of the string length to the running result.

ARRAYSUM:
	takes in 1) the current running result 2) the length of an array of 8 byte signed integers, and 3) a pointer to the beginning of the array of 8 byte signed integers.  This function calls the csum function to each element and updates the running result as it goes.  The function returns the final updated running result value.

ListSum:
	like arraysum but works on a list of elements.

ATOQ:
	Takes in 1) the current running result and 2) add a pointer to an ascii string.  It attempts to decode and ascii integer from the beginning of the string into an 8 byte signed value and then call the csum function on the running result and the decoded value updating the running result.

POPCNT:
	Takes in 1) the running result and 2) a signed integer value y.  The function should calculate the number of 1 bits in y and return the addition of this count and the running result

