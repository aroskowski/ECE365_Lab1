# Lab 1 ECE356 UTK 2024

This lab generates the fibonacci seqeunce of numbers using the Visual assembly language. Further parts of this lab further filter the output values based on certain criteria. 

Part 1 only generates the fibonacci number, at the index of the input. E.G. 0 = 0, 1 = 1, 2 = 1, 3 = 2, and so on. In comments this is labeled in the format of fib(index) = value

Part 2 limits outputs to only even/odd values. E.G. fib(3) = 3 because while the values 0 and 2 are skipped.  

Part 3 limits outputs to prime number values. Note that this language does not have division, so it is computationally intensive to find a prime. Typically the software will warn about an "infinite" loop when running with larger inputs. This can be ignored, its just the repeated subtraction that can cause these warnings. 
