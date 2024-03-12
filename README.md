# -sum-product-and-dict-with-single-input
#sum of values of even keys

'''
#problem1
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
r=0
for i in d:
  if i%2==0:
    r=r+d[i]
print(r)

#problem2
#product of values of odd keys
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
r=1
for i in d:
  if i%2!=0:
    r=r*d[i]
print(r)

#problem3
#dict with single input
d={}
n=int(input())
for i in range(1,n+1):
  d[i]=i+1
print(d)

