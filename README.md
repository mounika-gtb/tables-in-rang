# tables-in-rang
num,r1,r2=map(int,input().split())
if r1>r2:
    s=r2
    b=r1
else:
    s=r1
    b=r2
for i in range(s,b+1):
    print(num," * ",i,"=",num*i) 

