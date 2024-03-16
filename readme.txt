Python has no in-built class named Fraction. So if I want to have any mathematical output in simplified fraction, it is not possible.
So I took a step creating one, though small but still effective.





My Fraction class takes decimal or fraction number as input in string format.

Input: (string) decimal, or fraction
	eg: '2.02', '66/77'

output: (string) fraction number in simplified form.
	eg: '2.02' -> '101/50'   ,  '66/77' ->'6/7'






How to proceed?
Step 1. Create an object of Fraction class, and pass the argument. Accepts a single argument only.
	eg:  f= Fraction('2.02')

Step 2: Use the object/ reference variable to call the result() method. Done.
	eg: f.result()

	output: '101/50'