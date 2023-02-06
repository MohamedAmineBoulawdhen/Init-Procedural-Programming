# Dot Product Algorithm

## Problem Statement:
Calculate the dot product of two given vectors of IR 

## Procedure: dot_product
- Input: v1, v2 (two arrays representing vectors of IR)
- Output: ps (scalar dot product of v1 and v2)
- Steps:
  1. Initialize a variable `ps` to 0
  2. Loop through both arrays v1 and v2, and multiply each corresponding element and add the result to `ps`
  3. Return `ps`

## Algorithm: Orthogonal vectors
- Input: n (number of pairs of vectors), v1 and v2 (n pairs of arrays representing vectors of IR)
- Output: Orthogonal or Not Orthogonal for each pair of vectors
- Steps:
  1. Initialize a counter `i` to 0
  2. Loop through the pairs of vectors `i` from 0 to n-1, do the following:
    - a. Call the `dot_product` procedure with v1[i] and v2[i] as input
    - b. If the result of the dot product is 0, print "Orthogonal"
    - c. Else, print "Not Orthogonal"

## Algorithm: Orthogonal vectors using function
- Same as above algorithm with the difference of calling dot_product function instead of procedure.

