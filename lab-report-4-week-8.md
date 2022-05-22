# Lab Report 4
Here is my markdown-parse:
[link to my markdown-parse repository](https://github.com/janayagarcia/markdown-parser)

Here is someone's markdown-parse:
[link to my markdown-parse I reviewed in week 7](https://github.com/httrieu/markdown-parser)

## Each Test:
Snippet 1: 

VScode Expected Output: ["`google.com", "google.com", "ucsd.edu"]

Test:
![test1](snippet1test.png)

My implementation: Failed.
![test1](mytest1.png)

implementation I reviewed: Failed.
![test3fail](othertest1.png)


Snippet 2:

VScode Expected Output: ["a.com", "a.com(())", "example.com"]

Test: 
![test2](snippet2test.png)

My implementation:
Failed.
![test2fail](mytest2.png)

implementation I reviewed: Failed.
![test3fail](othertest2.png)


Snippet 3: 

VScode Expected Output: ["https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule"]

Test:
![test3](snippet3test.png)

My implementation: Failed.
![test3fail](mytest3.png)

implementation I reviewed: Failed.
![test3fail](othertest3.png)

## Questions
1. I do think you could add some lines of code to my markdown-parse file in order to make it work with code that has backticks. I would add an if statement that would see if there are backticks before the brackets. If so it should not add this link to the arraylist.

2. I do not think that the change could be done within 10 lines of code. This is because you have to account for at least 3 more scenarios where parenthesis,brackets and/or escaped brackets are ruining the functionality of your code. It is much more involed compared to solving the issue of backticks.

3. I think this would be possible to do within 10 lines. I say this because it sounds pretty simple to do in code. All you have to do is account for emtpy space which does not seem to hard. Maybe first save it all as a string that does not have spaces between brackets and parenthesis and then run through markdown-parser.

Code did not work for any snippets.