#1.missing alphabets
#i/p:welcome to geekstogeeks
#o/p:abdhijnpquvxyz
n="abcdefghijklmnopqrstuvwxyz"
str=input()
ans=" "
for i in n:
    if i not in str:
        ans=ans+i
print(ans)
