#!/bin/bash

# First-go-at-counting-to-ten
Counting to 10
#
# create a new folder called "counting"
mkdir counting
# change into the new counting folder
cd counting
# Create a new file in the counting folder call it counting.txt
touch counting.txt
# print the text counting to ten
echo "counting to ten" 
# write code that prints 1-10 new number each line in counting.txt 
echo "using for loop method # 1...."
for (( i=1; i<=10; i++))
do 
 echo "$i"
done 
