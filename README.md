# Aspire-systems
def aspire():
    n=int(input('Enter a number: '))
    if n%2==0:
        aspire()
    else:
        for i in range(n):
            for j in range(n):
                if i==j:
                    print(i+1,end=' ')
                else:
                    print(chr(97+j),end=' ')
            print()
aspire()
