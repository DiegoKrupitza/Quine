# What ist a Quine?

A [Quine](http://en.wikipedia.org/wiki/Quine_%28computing%29) is a self-replicating (compiled) programm. It generates a copy of its own source code.

I did this java quine back in 2004. It was hacked within less than a hour. I stumbled upon this recently which cleaning up my filesystem. 

The rationale behind building such a quine is prettry straight forward. 
You need a string which serves on the one hand as a rough outline of the sourcecode blocks and on the other hand as a reservoir for escape characters and keywords.
When printing to stdout you just copy characters or blocks form this string.