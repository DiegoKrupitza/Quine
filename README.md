# What ist a Quine?

A [Quine](http://en.wikipedia.org/wiki/Quine_%28computing%29) is a self-replicating (compiled) programm. It generates a copy of its own source code.

I did this Java quine back in [2004, at this time there was no Java example at Wikipedia like it is now](http://en.wikipedia.org/w/index.php?title=Quine_%28computing%29&oldid=9023942). So we wondered if it's possible to hack a Quine in Java within reasonable time. So I acceped the callange and put it on a test. It took way less time than expected, actually way less than a hour! 

But be warned the code is an ugly oneliner without any linebreaks. It's just a prove of concept. 

The rationale behind building such a quine is prettry straight forward. 
You need a string which serves on the one hand as a rough outline of the sourcecode and on the other hand as a reservoir for escape characters, keywords and whitespace.
When printing to stdout you just copy characters or blocks form this string.