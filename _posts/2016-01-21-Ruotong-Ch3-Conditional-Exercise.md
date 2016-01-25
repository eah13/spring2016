---
author: izayak
title: "Ruotong's Chapter3 Conditionals Exercises"
layout: post
---

Here is the embeded link from Trinket:
<iframe src="https://trinket.io/embed/python/138830866d" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

My thoughts:
1. I tried to print 'No input' if there is no input to variables 'hour', 'rate' etc. 
I searched online and find this on Stack Overflow:
http://stackoverflow.com/questions/18542107/python-test-if-raw-input-has-no-entry
Then I used the boolean operator 'not' to achieve that.
I also checked that 'not' has a higher precedence than 'or' through the document (part 5.15):
https://docs.python.org/2/reference/expressions.html
Or the following link neatly provide only the table:
http://www.mathcs.emory.edu/~valerie/courses/fall10/155/resources/op_precedence.html

My questions:
1. For exercise 3, for score less than 0 or greater than 10, I print 'Bad score' in the try part. Should that be put in except part? 
I also add a comment in the Trinket file to indicate that question's position.
2. About the print statement, can I use it the way like in Python i.e. print(' ', ' ', ...)? Or I can only use like this: print ' '+' '+... ? 
3. Can we format our post? Such as add pictures and move to the next line at specific places?