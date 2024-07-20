# Find Valid Matrix Given Row and Column Sums

LeetCode Q # 1605.

You are given two arrays rowSum and colSum of non-negative integers where rowSum[i] is the sum of the elements in the ith row and colSum[j] is the sum of the elements of the jth column of a 2D matrix. In other words, you do not know the elements of the matrix, but you do know the sums of each row and column.

Find any matrix of non-negative integers of size rowSum.length x colSum.length that satisfies the rowSum and colSum requirements.

Return a 2D array representing any matrix that fulfills the requirements. It's guaranteed that at least one matrix that fulfills the requirements exists.

Example 1:

> Input: rowSum = [3,8], colSum = [4,7]</br>
> Output: [[3,0], [1,7]]</br>
> Explanation: </br>
> 0th row: 3 + 0 = 3 == rowSum[0]</br>
> 1st row: 1 + 7 = 8 == rowSum[1]</br>
> 0th column: 3 + 1 = 4 == colSum[0]</br>
> 1st column: 0 + 7 = 7 == colSum[1]</br>
> The row and column sums match, and all matrix elements are non-negative.</br>
> Another possible matrix is: [[1,2], [3,5]]

Example 2:

> Input: rowSum = [5,7,10], colSum = [8,6,8]</br>
> Output: [[0,5,0], [6,1,0], [2,0,8]]

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/b55f6e26-1c2c-4168-870a-8f54c485bc04)

  Time complexity: O(m*n).</br>Space complexity: O(m*n).
</div>
