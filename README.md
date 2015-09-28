
Keyword Module
===============

Did you know that there are 33 keywords in Python?
Knowing about them will prevent you from making the mistake of naming your variable with one.
Here is how you could use this module;

**************************
**Step 1: Import Module:**
**************************
To use this module, import it first. Following is the command:

>>> import keyword

******************************
**Step 2: List all keywords:**
******************************
If you wish to view the complete list of all the keywords, you could use the following command;

>>> keyword.kwlist

['and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'exec', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'not', 'or', 'pass', 'print', 'raise', 'return', 'try', 'while', 'with', 'yield']

*************************************************************
**Step 3: Check any word to ensure that it’s not a keyword:**
*************************************************************
This is how you could check if any word is a keyword or not. Type your word as a string, enclose it in a set of parenthesis, if it is a keyword, Python will return a 'True', if it's not a keyword, 'False' will be returned.

>>> keyword.iskeyword(‘global’)

True

>>> keyword.iskeyword(‘cheese’)

False

************************
**Step 4: Undo Import:**
************************
After having used the module, you could undo your import by using the following command. 

>>> del keyword


***************
**References:**
***************
https://www.youtube.com/watch?v=B-7exsBxFlA

https://docs.python.org/3/library/keyword.html#module-keyword
