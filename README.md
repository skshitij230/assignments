# assignments
all assigment for data science
assignment1
August 27, 2023
[2]: s = "kshitij"
[3]: type(s)
[3]: str
[4]: l = ["kshitij", "18", "data science", "2.0", True]
[5]: type(l)
[5]: list
[6]: n = 23.567
[7]: type(n)
[7]: float
[8]: t = ("kshitij", 18, "data science", 2.0, True)
[9]: type(t)
[9]: tuple
[10]: var1 = ''
[11]: type(var1)
[11]: str
[12]: var2 = '[DS,ML,Python]'
[13]: type(var2)
[13]: str
[14]: var3 = ['DS','ML','Python']
1
[15]: type(var3)
[15]: list
[16]: var4 = 1
[17]: type(var4)
[17]: int
[18]: a = 20
b = 10
c = 20/10
[19]: c
[19]: 2.0
[20]: a1 = 20
b1 = 10
c1 = 20%10
[21]: c1
[21]: 0
[22]: a2 = 20
b2 = 10
c2 = 20//10
[23]: c2
[23]: 2
[24]: a4 = 20
b4 = 10
c4 = 20**10
[25]: c4
[25]: 10240000000000
[26]: l1 = ["kshitij", 18, 15+4j, True, [1,2,3,4,4], (2,4,5,6), 23.456,␣
↪[1,2,3,(4,5,6),7,9], False, "me"]
[30]: for i in l1:
print(i)
2
kshitij
18
(15+4j)
True
[1, 2, 3, 4, 4]
(2, 4, 5, 6)
23.456
[1, 2, 3, (4, 5, 6), 7, 9]
False
me
[1]: a = int(input())
b = int(input())
count = 0
while a%b == 0:
a = a//b
count+=1
if count>0:
print(f"{a} is divisible by {b} a total of {count} times")
else:
print(f"{a} is not divisible by {b}")
23
34
23 is not divisible by 34
[2]: l2 = [1,2,3,4,6,8,9,21,12,45,67,89,90,45,32,33,99,66,54,30,5,6,7,8,9]
[4]: for i in l2:
if i%3 == 0:
print("divisible by 3")
else:
print("not divisible by 3")
not divisible by 3
not divisible by 3
divisible by 3
not divisible by 3
divisible by 3
not divisible by 3
divisible by 3
divisible by 3
divisible by 3
divisible by 3
not divisible by 3
not divisible by 3
divisible by 3
3
divisible by 3
not divisible by 3
divisible by 3
divisible by 3
divisible by 3
divisible by 3
divisible by 3
not divisible by 3
divisible by 3
not divisible by 3
not divisible by 3
divisible by 3
[5]: l2
[5]: [1,
2,
3,
4,
6,
8,
9,
21,
12,
45,
67,
89,
90,
45,
32,
33,
99,
66,
54,
30,
5,
6,
7,
8,
9]
[6]: l2[
3
]
=
5
[7]: l2
[7]: [1,
2,
4
3,
5,
6,
8,
9,
21,
12,
45,
67,
89,
90,
45,
32,
33,
99,
66,
54,
30,
5,
6,
7,
8,
9]
[11]: t1 = ("kshitij", 18, "data science", 2.0, True)
[12]: t1[1] = 19
---------------------------------------------------------------------------
TypeError Traceback (most recent call last)
Cell In[12], line 1
----> 1 t1[1] = 19
TypeError: 'tuple' object does not support item assignment
[ ]:
5
