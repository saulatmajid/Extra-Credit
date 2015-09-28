

Keyword Module
==============

Did you know that there are 33 keywords in Python?
Knowing about them will prevent you from making the mistake of naming your variable with one.
Here is how you could use this module.


Step 1: Import Module:
======================

import keyword

Step 2: List all keywords:
==========================

>>> keyword.kwlist
['and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'exec', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'not', 'or', 'pass', 'print', 'raise', 'return', 'try', 'while', 'with', 'yield']

Step 3: Check any word to ensure that it’s not a keyword:
=========================================================

>>> keyword.iskeyword(‘global’)

True

>>> keyword.iskeyword(‘cheese’)

False

Step 4: Undo Import:
====================

del keyword



Reference:
==========
https://www.youtube.com/watch?v=B-7exsBxFlA

https://docs.python.org/3/library/keyword.html#module-keyword
