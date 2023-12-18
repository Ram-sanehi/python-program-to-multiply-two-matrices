# python-program-to-multiply-two-matrices
<br># Program to multiply two matrices using nested loops

<br># 3x3 matrix
<br>X = [[12,7,3],
 <br>   [4 ,5,6],
<br>   [7 ,8,9]]
<br># 3x4 matrix
<br>Y = [[5,8,1,2],
 <br>   [6,7,3,0],
 <br>   [4,5,9,1]]
<br># result is 3x4
<br>result = [[0,0,0,0],
     <br>    [0,0,0,0],
      <br>   [0,0,0,0]]

<br># iterate through rows of X
<br>for i in range(len(X)):
<br>   # iterate through columns of Y
<br>   for j in range(len(Y[0])):
 <br>     # iterate through rows of Y
<br>      for k in range(len(Y)):
         <br>  result[i][j] += X[i][k] * Y[k][j]

<br>for r in result:
  <br> print(r)
