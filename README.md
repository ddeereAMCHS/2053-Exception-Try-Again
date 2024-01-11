# Exception Try Again

## Due: Wed 1/17 at 11:59 PM

- Create a program called `ExceptionTryAgain.java`
- Prompt the user for a filename until the user enters the name of a file that exists
- The first line of the file contains a number that should specify how many lines of data are in the file
  - If the actual number of lines of data in the file is different from this number, print that the data is incorrect
- Read in all the lines and store them in an ArrayList of integers
  - If there is any value that is not an integer, but is a double, read in the integer part of the double
  - For any other value that is not an integer or a double, store the length of that line
- Print out the sum of all values in the ArrayList as well as the number of lines that had to be read in differently

***Example Input:***\
gibberish\
stillBad.txt\
input1.txt\
***Example Contents of input1.txt:***\
9\
3\
4\
cat\
5.7\
dog\
8\
12\
elephant\
7.5\
2\
***Example Output:***\
The value in the file is not representative of the amount of data\
Sum of values: 55\
Number of doubles read in as ints: 2\
Number of non-numeric values: 3
