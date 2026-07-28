## Learning about the Variables
echo "hello world" #prints the msg

Simple bash script:
#!/bin/bash
echo "hello world" #prints the msg

Assigning value to the variable:
name="dhruvi"
echo $name #prints the value of the variable
echo "my name is $name" #prints the msg and the value of the variable
- Read can also be used

Concatenation:
greeting="hello"
greet="world"
echo $greeting $greet #prints the msg and the value of the variable

Airthmetic:
num1= 5
num2= 10
sum=$((num1) + (num2))
echo "the sum is $sum"

String example
greeting="Hello, World!"
name="Alice"
full_greeting="$greeting, $name!"
echo $full_greeting

Number example
num1=5
num2=10
sum=$((num1 + num2))
difference=$((num2 - num1))
product=$((num1 * num2))
quotient=$((num2 / num1))
echo "Sum: $sum, Difference: $difference, Product: $product, Quotient: $quotient"