# Reflection  

My pseudocode is messy and I think I was too focused on making it like real code. 
I think my time could have been better spent describing the functionality, but 
on the other hand, it's good to think about the needed structure, even if I am not 
getting it 100% right.  

My preamble in the .txt file describes what I want my code to do, and the rest is general 
plan on how I might start to design the prescribed functionality.  

insert() function pseudo on line: 69   
remove() function pseudo on line: 88  
get() function pseudo on line: 101  

test module plan/pseudo begins on line: 113  

Big O analysis is on lines : 63, 86, and 99   




# NOTES TO SELF  

Do not neglect testing!!!  

Watching this week's videos I realized I need to read the instructions more carefully. I will, and must, write tests for this assignment, and I intend to include them in the design phase.  

Remember to do line-by-line analysis for this assignment! (bigO).  

Use ".hpp" for header file, not ".h"  

remember "#pragma once"  

Use References (and reference them):  
  - https://www.bigocheatsheet.com/  
  - https://en.wikipedia.org/wiki/Computational_complexity  
  - https://visualgo.net/en/sorting?slide=1  


Consider binary search for search function!  



# Instructions  
    Create a linked-list that allows:  

        an add function that takes a value and inserts it into a given position into the list  
        (example: myList.add(someValue, somePosition) )  

        a remove function that takes a position and removes the value stored at that position of the list and returns it  
        (example: myList.remove(somePosition) )  

        a get function that takes a position and returns that value without removing it  
        (example: myList.get(somePosition) )  

    Be sure to include at least one test function for each piece of functionality that should verify that your code is working!     This should be at least one test per behavior, likely more.  You can make these tests in a source file with a main where your   tests are either directly in the main or inside their own standalone functions (please do not neglect the importance of    testing!)  

    Once you have implemented and tested your code, add to the README file what line(s) of code or inputs and outputs show your   work meeting each of the above requirements (or better, include a small screen snip of where it meets the requirement!).  

    (Note: we will cover the analysis of some of this in class next week, then we will have you analyze the next ones!)  
    Attempt to analyze the complexity of your implementation with line-by-line analysis,  

Note: This assignment is to get you to think about the trade-offs that we may have to weigh before using one structure over another  