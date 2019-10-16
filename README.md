task1
n = int(input())

i = 0

while i < n:
    command = str(input())

    res = 23 * len(command)

    print(res)



task 2
a = float(input())
b = float(input())
c = str(input())

if c == "+":
    print(a+b)
elif c == "-":
    print(a-b)
elif c == "*":
    print(a*b)
elif c == "/":
  
    if b == 0:
        print("ЫЫЫЫЫЫЫ")
    else:
        print(a/b)
        
else:
    print("ЫЫЫЫЫЫЫ")
    
    
    
task 3
    x1 = int(input())
y1 = int(input())

x2 = int(input())
y2 = int(input())

x3 = x2 - x1
y3 = y2 - y1

if (x3 == 5 or x3 == 2 or x3 == -5 or x3 == -2) and (y3 == 5 or y3 == 2 or y3 == -5 or y3 == -2):
    print("YESS")
else:
    print("no no")
    
    
    
task 4
    1 = int(input())
y1 = int(input())

x2 = int(input())
y2 = int(input())

if x1 == x2 or y1 == y2 or ((x2 % x1) > 0 and (y2 % y1) > 0):
    print("Yes")
else:
    print("No")
