def fibonacci_series(n):
    a,b=0,1
    if n==0:
        print("Enter the number greater than 0")
    elif n==1:
        print(a)
    else:
        print(a,b,end=" ")
        for i in range(n-2):
            sum=a+b
            a,b=b,sum
            print(sum,end=" ")
n=int(input("Enter how many fibonacci numbers you want to generate:"))
fibonacci_series(n)
