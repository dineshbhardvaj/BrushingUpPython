
About Numbers

# Floor Division
7//4 --> result will be one instead of 1.75
The // operator (two forward slashes) truncates the decimal without rounding, and returns an integer result.


# Can also do roots this way
4**0.5 --> 2


The names you use when creating these labels need to follow a few rules:

1. Names can not start with a number.
2. There can be no spaces in the name, use _ instead.
3. Can't use any of these symbols :'",<>/?|\()!@#$%^&*~-+
4. It's considered best practice (PEP8) that names are lowercase.
5. Avoid using the characters 'l' (lowercase letter el), 'O' (uppercase letter oh), 
   or 'I' (uppercase letter eye) as single character variable names.
6. Avoid using words that have special meaning in Python like "list" and "str"

About Strings

# We can use this to print a string backwards
s = Hello World
s[::-1] -- > dlroW olleH


#string formating
print('Floating point numbers: %25.2f' %(13.144)) 
--> Floating point numbers: 13.14

print('Floating point numbers: %1.5f' %(13.144)) 
-->   Floating point numbers: 13.14400

print('First: %s, Second: %5.2f, Third: %r' %('hi!',3.1415,'bye!')) 
-->  First: hi!, Second:  3.14, Third: 'bye!'

print('The {2} {1} {0}'.format('fox','brown','quick'))
--> The quick brown foxThe quick brown fox

