# RoutingTableCalculator
A routing table calculator using distance vector and distance vector

# input and output sample
X
Y
Z
DISTANCEVECTOR
X Z 8
X Y 2
Y Z 3
UPDATE
A Y 10
END
X Distance Table at t=0
        Y       Z
Y       2       INF
Z       INF     8

Y Distance Table at t=0
        X       Z
X       2       INF
Z       INF     3

Z Distance Table at t=0
        X       Y
X       8       INF
Y       INF     3

X Distance Table at t=1
        Y       Z
Y       2       11
Z       5       8

Y Distance Table at t=1
        X       Z
X       2       11
Z       10      3

Z Distance Table at t=1
        X       Y
X       8       5
Y       10      3

X Distance Table at t=2
        Y       Z
Y       2       11
Z       5       8

Y Distance Table at t=2
        X       Z
X       2       8
Z       7       3

Z Distance Table at t=2
        X       Y
X       8       5
Y       10      3

X Routing Table:
Y,Y,2
Z,Y,5

Y Routing Table:
X,X,2
Z,Z,3

Z Routing Table:
X,Y,5
Y,Y,3

A Distance Table at t=3
        X       Y       Z
X       INF     INF     INF
Y       INF     10      INF
Z       INF     INF     INF

X Distance Table at t=3
        A       Y       Z
A       INF     INF     INF
Y       INF     2       11
Z       INF     5       8

Y Distance Table at t=3
        A       X       Z
A       10      INF     INF
X       INF     2       8
Z       INF     7       3

Z Distance Table at t=3
        A       X       Y
A       INF     INF     INF
X       INF     8       5
Y       INF     10      3

A Distance Table at t=4
        X       Y       Z
X       INF     12      INF
Y       INF     10      INF
Z       INF     13      INF

X Distance Table at t=4
        A       Y       Z
A       INF     12      INF
Y       INF     2       11
Z       INF     5       8

Y Distance Table at t=4
        A       X       Z
A       10      INF     INF
X       INF     2       8
Z       INF     7       3

Z Distance Table at t=4
        A       X       Y
A       INF     INF     13
X       INF     8       5
Y       INF     10      3

A Distance Table at t=5
        X       Y       Z
X       INF     12      INF
Y       INF     10      INF
Z       INF     13      INF

X Distance Table at t=5
        A       Y       Z
A       INF     12      21
Y       INF     2       11
Z       INF     5       8

Y Distance Table at t=5
        A       X       Z
A       10      14      16
X       22      2       8
Z       23      7       3

Z Distance Table at t=5
        A       X       Y
A       INF     20      13
X       INF     8       5
Y       INF     10      3

A Routing Table:
X,Y,12
Y,Y,10
Z,Y,13

X Routing Table:
A,Y,12
Y,Y,2
Z,Y,5

Y Routing Table:
A,A,10
X,X,2
Z,Z,3

Z Routing Table:
A,Y,13
X,Y,5
Y,Y,3
