# Autocorrect

# Building the model

1. Identify the misspelled word
2. Find strings n edit distance away
3. Filter candidates
4. Calculating word probabilities

# Minimum edit distance

Minimum edit distance allows you to:

- Evaluate similarity between two strings

- Find the minimum number of edits between two strings

- Implement spelling correction, document similarity, machine translation, DNA sequencing, and more

D[i,j] = D[i-1, j] + del_cost: this indicates you want to populate the current cell (i,j) by using the cost in the cell found directly above.

D[i,j] = D[i, j-1] + ins_cost: this indicates you want to populate the current cell (i,j) by using the cost in the cell found directly to its left.

D[i,j] = D[i-1, j-1] + rep_cost: the rep cost can be 2 or 0 depending if you are going to actually replace it or not.

![image](https://user-images.githubusercontent.com/63448884/221516412-406443cd-cba8-45ba-9d05-17a184d148d6.png)

