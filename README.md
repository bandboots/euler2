fib = [ 1 , 2 ]
eve = [2]
i   = 0

while i < 4000000:
	i = fib[-1] + fib[-2]
	fib.append ( i )
	if i % 2 == 0:
        	eve.append ( i )
        	#that.append
print ( sum ( eve ) )
