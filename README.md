# list
#print list
n=int(input())
a=[]
for i in range(n):
  x=int(input())
  a.append(x)
print(a)

#reverse list
n=int(input())
a=[]
for i in range(n):
  x=int(input())
  a.insert(0,x)
print(a)

n=int(input())
a=list(map(int,input().split()))
print(a)

#FINDING INDEX
n=int(input())
a=list(map(int,input().split()))
x=int(input())
res=None
for i in range(n):
  if x == a[i]:
    res =i
if res == None:
  print("element not found")
else:
  print(res)
