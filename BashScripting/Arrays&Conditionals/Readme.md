## Arrays
Array example
fruits=("apple" "banana" "cherry")
for fruit in "${fruits[@]}"; do
  echo $fruit

Associative array example
declare -A colors
colors[apple]="red"
colors[banana]="yellow"
colors[grape]="purple"
unset colors[banana]
echo ${colors[apple]} # red
echo ${colors[grape]} # purple
done

Comparison Operators
-eq: Equal to
-ne: Not equal to
-lt: Less than
-le: Less than or equal to
-gt: Greater than
-ge: Greater than or equal to

String Comparison Operators
=: Equal to
!=: Not equal to
<: Less than, in ASCII alphabetical order
>: Greater than, in ASCII alphabetical order

Arithmetic Operators
+: Addition
-: Subtraction
*: Multiplication
/: Division
%: Modulus (remainder of division)

Logical Operators
&&: Logical AND
||: Logical OR
!: Logical NOT

File Test Operators
-e: Checks if a file exists
-d: Checks if a directory exists
-f: Checks if a file is a regular file
-s: Checks if a file is not empty

Basic if statement
num=15
if [ $num -gt 10 ]; then
  echo "Number is greater than 10"
fi

If...else statement
num=8
if [ $num -gt 10 ]
then
  echo "Number is greater than 10"
else
  echo "Number is 10 or less"
fi

If...elif...else statement
num=10
if [ $num -gt 10 ]
then
  echo "Number is greater than 10"
elif [ $num -eq 10 ] 
then
  echo "Number is exactly 10"
else
  echo "Number is less than 10"
fi

Nested if statement
num=5
if [ $num -gt 0 ] 
then
  if [ $num -lt 10 ] 
then
    echo "Number is between 1 and 9"
  fi
fi