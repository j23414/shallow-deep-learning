### Setup Dependencies

```
conda env create -f environment.yml -p ${PWD}/DLwkshp_env
source activate ${PWD}/DLwkshp_env
```

### Python

Using two nested for loops, create a list M of seven lists with no repeating values such that element M[i][j] = 5 * i + j

```
import numpy
i = 4
j = 5
M = numpy.zeros((i,j))

for row in range(0, i):
  for col in range(0, j):
    M[row,col] = 5*row + col

M
```

output:

```
array([[ 0.,  1.,  2.,  3.,  4.],
       [ 5.,  6.,  7.,  8.,  9.],
       [10., 11., 12., 13., 14.],
       [15., 16., 17., 18., 19.]])
```

Alternative answer?

```
M=[]
for i in range(0,7):
    for j in range(0,1):
        M.append([5*i+j])

M
```

output:

```
[[0], [5], [10], [15], [20], [25], [30]]
```

This is a test of windows atom, required a git key.
