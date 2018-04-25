1. A 2D array is also called a 2D matrix.
2. The main diagonal for a 3x3 Matrix is the elements where i = j so for a 3x3 Matrix it would be elements with index 0,0/1,1/2,2.
3. All elements below the main diagonal share the property i > j. i.e. 1,0/2,0/2,1
4. All elements above the main diagonal share the property i < j. i.e. 0,1/0,2/1,2
5. The secondary diagonal for a 3x3 Matrix is the elements where i + j = num rows -1  so for a 3x3 Matrix it would be elements with index 0,2/1,1/2,0.
6. All elements below the secondary diagonal share the property i+j >= num rows. i.e. 1,2/2,1/2,2
7. All elements above the secondary diagonal share the property i + j < num rows. i.e. 0,0/0,1/1,0.


where
i = the index of the row and
j = the index of the column
