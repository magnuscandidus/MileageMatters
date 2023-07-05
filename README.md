# MileageMatters
# cook your dish here
t=int(input())
while t:
    n,x,y,a,b=map(int,input().split())
    if(((n/a)*x)<((n/b)*y)):
        print("PETROL")
    elif(((n/a)*x)>((n/b)*y)):
        print("DIeSEL")
    else:
        print("ANY")
    t-=1
