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

for row in [0 : i-1]:
  print(row)
```

