# ChefAndRemisseness
# cook your dish here
t=int(input())
while t:
    a,b=map(int,input().split())
    if(a>b):
        print(max(a,b) , a+b)
    else:
        print(max(a,b) , a+b)
    t-=1
