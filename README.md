# DSAsgmnt1
CSC 300 Data Structures 
Assignment - A1

Using c-style strings

Read a file
 - less than 500 strings
 - less than 100 chars in each string

keep track of
  Original order
  Alphabetical order


Interactive:
  - ask for command option
  - then details for command as needed


Initial commands:

1 print list original
2 print list sorted
3 get by original
    ask for number, 5  ... get 5th item from original
4 get by sorted
    ask for number
5 add a string
    ask for string, store it
6 remove a string by orig #
7 remove a string by sort #

0 quit


Rules
 - can only store the string once
 - allocate all space in main at creation time
 - menu can be in main, but better as function
 - if ask for out of range, just print message

sort
 - case insensitive
 - alphabetical ( by ascii for non letters )
