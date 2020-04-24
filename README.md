# SCAMP
# Using Python, write out a function to output the fibbonacci sequence of a given number

"""The code below outputs the list of the range of a number 31, which runs in a sequence of multiples of 5. It starts from the the first number 0 and stops at the second number (31) subtracted by 1. The sequence of numbers is separated by a third number 5"""

def fibbonacci_sequence(number, sequence):
    return list(range(0, number, sequence))
fibbonacci_sequence(31, 5)
