## Python-Concept

# 1. List Comprehension

Input Values are : tmp = [29.84087, 34.3745, 34.91104, 35.72471, 19.31632, 728.1475, None, 404.3762]

Output values should be = [2, 3, 4, 5, 1, 7, 6]

Python Code to achieve it = 

tmp = [value for value in tmp if value]

print ([sorted(tmp, key=lambda x: (x is None, x), reverse=False).index(x) + 1 for x in tmp])
