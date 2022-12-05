# Number-of-prime-numbers
n=int(input('Enter any number:'))
count=0
while(n!=1):
    i=2
    factor=2
    while(i<n):
        if(n%i==0):
            factor=factor+1
            break
        i=i+1
    if(factor==2):
         count=count+1
         print(n)
    n=n-1
print('There are',count,'prime numbers.') 
