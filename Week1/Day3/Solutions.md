#PROBLEM 7

```
PSEUDOCODE:-
Integer a = 6 + 6
Integer b = 1 + 1
Integer result = a + b
print(result)

APPROACH:-
a = 6 + 6 = 12  
b = 1 + 1 = 2  
result = a + b = 12 + 2 = 14

ANS:-
14
```

-----------------------------------------------------------------
#PROBLEM 8

```
PSEUDOCODE:-
Integer a = 2
Integer b = 5
Integer c = 10
while (b > 0) {
    c = c - a
    b = b - 1
}
print(c)

APPROACH:-
Loop runs 5 times:
Initial: c = 10  
Each time: c = c - 2  
After 5 times: 10 - 2*5 = 0

ANS:-
0
```

-----------------------------------------------------------------

#PROBLEM 9

```
PSEUDOCODE:-
Integer a = 2
Integer b = 2
Integer c = 10
if ((a == b) OR (c < 5)) {
    print(a + b + c)
} else {
    print(a * b * c)
}

APPROACH:-
(a == b) is true → condition satisfied  
Execute: a + b + c = 2 + 2 + 10 = 14

ANS:-
14
```

-----------------------------------------------------------------
#PROBLEM 10

```
PSEUDOCODE:-
Integer a = 4
Integer b = 2
Integer c = 0
while (a > 0) {
    if (a % 2 == 0) {
        c = c + b
    }
    a = a - 1
}
print(c)

APPROACH:-
a = 4, 3, 2, 1 → loop runs 4 times  
Even a: 4 and 2 → c = c + 2 two times → c = 0 + 2 + 2 = 4

ANS:-
4

```
-----------------------------------------------------------------
