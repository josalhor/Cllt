I have found the following transformation online that I document here:
Assume integer division
x = x/2 if x % 2 == 0 else 3*x+1
Is equivalent to:
x = (x*3+1)/(6^(x%2))
