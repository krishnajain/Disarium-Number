# Disarium-Number

A number is said to be the Disarium number when the sum of its digit raised to the power of their respective positions is equal to the number itself.


For example, 175 is a Disarium number as follows

11 + 72 + 53 = 1 + 49 + 125 = 175


Some of the other examples of Disarium number are 89, 135, 518 etc.

To find whether given number is Disarium or not, calculate the sum of digits powered with their respective positions. If the sum is equal to the original number then, the given number is Disarium number.


ALGORITHM

    calculateLength() counts the digits present in a number.


    Use a while loop to check whether the number is not equal to 0.


    Divide the number by 10 and increment the variable length by 1.


    Return length.


    Define and initialize variable num.


    Make a copy of num by storing the value of num in n.


    Using while loop calculates remainder rem repeatedly by dividing num with 10.


    Calculate the value of rem raised to power its position , and store the computed value in a variable sum.


    Check whether sum is equal to number. If yes, then given number is Disarium number. Else, it is not a Disarium number.
