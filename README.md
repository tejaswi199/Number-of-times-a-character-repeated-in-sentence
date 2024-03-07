#Approach-1
s=input()
c=0
x=input()
for i in range(len(s)):
  if x==s[i]:
    c=c+1 
print(c)

#Approach-2
s=input()
c=0
x=input()
for i in s:
  if x==i:
    c=c+1 
print(c)

#Approach-3
s=input()
x=input()
print(s.count(x))
