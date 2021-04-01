a = int(input())
b = int(input())
c = int(input())
v = a * b * c
s = a * b + a * c + b * c / 2

if a <= 0 or b <= 0 or c <= 0:
    print("The inputs are wrong")
else:
    print(v)
    print(s)
