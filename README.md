NQueens.ps
==================

Three implementations of the famous nqueens problem, written in postscript.

## N-Queens Simple

This is the simplest version of the nqueens problem. It just prints out the
number of solutions for a given number of queens:

```
gs -q nqueens-simple.ps 
Please enter the # of queens?
>: 8
92
```

## N-Queens Print Board

This version additionally prints out the solutions:

```
gs -q nqueens-printboard.ps 
Please enter the # of queens?
>: 4
New board:
*D**
***D
D***
**D*
New board:
**D*
D***
***D
*D**
```

## N-Queens Unique

This version calculates not only the number of total solutions, but also the
number of solutions that are unique in relation to all symmetry operations
(rotations reflections) of the board.

```
gs -q nqueens-unique.ps 
Please enter the # of queens?
>: 8
92
12
```
