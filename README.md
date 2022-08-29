def fib(n):
    if n< 0 or int(n) !=n:
	   return "Not defined"
	elif n== 0 or n== 1:
	     return n
    else:
	    return fib(n-1)+fib(2)
		
n=int(input('Enter the number:\n'))
print("Fibonacci series:",end="")
for i in range(0,n):
    print(fib(i),end=" ")
