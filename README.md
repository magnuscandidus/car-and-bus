# car-and-bus
# cook your dish here
t=int(input())
for p in range(t):
    x,y=map(int,input().split())
    if x>y:
        print("car")
    elif x<y:
            print("bike")
    else:
        print("same")
