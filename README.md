# BrainF-K-Even-Or-Odd
A BrainF**K program that checks whether a single digit is even or odd


# ECE560 Questions
## Describe what your program does

The program receives a single digit from the user and outputs whether the digit is even or odd. 

## The language you wrote it in

I wrote this program in the BrainF**K programming language.

## The unusual aspects of your language that you had to understand to write your program.

The unsual aspects of the language I had to understand were
- Using conditional statements only comprised of "is the current cell not 0"
  - I had to determine ways to represent the condition of whether the input was even or odd in a way that relied on one of two cells to not be 0
- Doing math (i.e. taking the modulus 2 of a number)
  - I had to determine how to take the modulus 2 of a number while only having the mathematical operations of subtracting by one and adding by one
  - I also had to determine how to take the output of this modulus and return it in either one of two cells as mentioned above
- How to avoid infinite loops
    - One of the biggest obstacles I had while developing this program was debugging when there was an infinite loop and how to achieve the desired math without accidentally creating an infinite loop
    - One example was for the modulus 2 code, I had to determine how to subtract the input digit by 2 to determine the remainder without going below 0, which would mean that the current cell was still not 0

## Inputs to and outputs from your program

The program accepts one character from the user as input and outputs the strings "EVEN" or "ODD" respectively depending on the digit.

The program can be run at https://copy.sh/brainfuck/ 

Here is a screenshot of the input and output
![image](https://github.com/user-attachments/assets/36e52141-2d50-473f-b4e7-6f83e46f1a44)
![image](https://github.com/user-attachments/assets/a3f2dd38-a0ed-4f85-9ab5-a9fa950f0e00)


