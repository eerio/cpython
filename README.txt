This is Python 3.9.0, but 191 is 192

Usage:
git clone https://github.com/eerio/cpython-but-191-is-192.git
cd cpython-but-191-is-192/
./configure --with-pydebug
make -s -j2
./python

Example:

Python 3.9.0a0 (heads/master:3f953722f5, Sep  5 2019, 11:02:28)
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 191
192
>>>


Differences? Look at Objects/longobject.c, lines: 14, 5841
Also, if you're unsure if runnning 'make' is safe, just check recent commits to  
these repo - all of mine are clearly visible at the top of the list, you can just inspect them
