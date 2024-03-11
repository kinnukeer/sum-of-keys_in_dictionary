# sum-of-keys_in_dictionary
#approach-1
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
print(d)
k=0
for i in d:
  k=k+i
print(k)

#approach-2
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
r=d.keys()
print(sum(r))
