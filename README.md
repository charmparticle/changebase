# changebase
A simple python script to change the numeric base of some arbitrary number in some arbitrary numeric base between 2 and 64.

Use it like this:

#changebase assumes you want base10, like a normal human
changebase ZAZZLE -f 36
2134791410

#you can also be explicit
changebase BOOGIE -f 25 -t 10 
117182339

#get wild
changebase All+Your+Base -f 64 -t 2
100101100101111110011000101000101110101011111110000001011010101100011110

#you can also use pipes
changebase RAD -f 34 -t 2 | changebase - -f 2 -t 34
RAD
