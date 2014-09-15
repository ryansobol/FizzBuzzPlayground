# FizzBuzz

A single method that takes one number as an argument. For multiples of three it returns “Fizz”, for multiples of five it returns “Buzz”.

For numbers which are multiples of both three and five it returns “FizzBuzz”, and in all other cases return the number.

I have included a minimum amount of input checking and added a very simple RSpec file to test the basic cases.


#### Considerations:

Tonight I'll try to refactor the method to a simpler expression.

The key in this case was to place first the divisible by 15 condition before checking for divisibility by 3 and 5, as to outputting "FizzBuzz" first.

I considered making an object playground that just loops in wait for a STDIN, and calls the fizzbuzz method when the user inputs a number. But I run into problems in the way to create the appropriate spec (stubing the :gets call), so I went for the simplest working code.
