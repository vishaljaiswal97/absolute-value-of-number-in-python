#absulute number
def ab():
    a=int(input())
    if a>0:
        for i in range(1,a+1):
            print(i)
    if a<0:
        a=abs(a)
        for j in range(1,a+1):
            print(abs(j))
ab()

        
