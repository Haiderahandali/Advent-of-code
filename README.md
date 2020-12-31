# AOC Day one
#
### The first problem was to find if the sum of 2 numbers (problem a) is equal to 2020, and problem (b) was if the sum of 3 numbers

### I solved it first, using Brute force solution (always get it to run, then optimize is my rule of thump)

### I parsed the input, by copy pasting the list first into a file (data.log) and then running the command
### paste -sd, data.log >> aoc_day_1.cpp 
### that generated a comma separated list of numbers which I just then put them into a vector
 
### my algorithm was in form of to find 3 numbers that sum up to 2020, the following should apply
### 2020 - **number1** - **number2** - **number3** = 0
### and I checked if **2020** -  **number1** does exist in the second vector (which is empty in the beginning)
### if it doesn't exist I just add the number to vector, and same goes for the third vector. 
