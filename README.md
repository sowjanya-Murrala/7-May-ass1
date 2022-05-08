n=int(input())
l=[]
d={}
for i in range(n):
    x=int(input())
    l.append(x)
j=1 
for i in l:
    if i % 2 ==0:
    d[j]=i 
    j=j+i 
print('yes')
if i%2 != 0:
    d[j]=i    
    
