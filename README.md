l=[]
n=int(input())
for i in range(n):
    e=int(input())
    l.append(e)
max=l[0]
for i in range(1,n):
      if l[i]>max:
            max=l[i]
print('max',max)
min=[0]
for i in range(1,n):
      if l[i]<min:
           min=l[i]
print('min',min)
            
