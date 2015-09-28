# Radix Converter
A simple (and hacky) automatic converter between hexadecimal, decimal, and binary

I created this script during CS discussion, because I didn't feel like doing all the conversions by hand. It consists of simple functions like "bin_to_dec", which convert a string of a number in one format into a string of the same number in the other. The binary-hexadecimal conversions use a very hacky string dictionary (and its automatically generated inverse), mapping strings of four binary digits to one hex digit, and vice versa. The binary-decimal conversions actually use the underlying math. Finally, the decimal-hexadecimal conversions simply take advantage of the already written conversion functions between the other pairings.

The rest of the code is simply an infinite loop which asks for a number, figures out its current format from its prefix, and outputs the converted versions. 

