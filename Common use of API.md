# Common Use of Java API

## Sort 2D Array 
```
#int[][] array 
    Arrays.sort(
        array, (i1, i2) ->    
            Integer.compare(i1[0], i2[0])); 

```
^ sorted by the first integer

## List to Array 
```
# List<int[]> res;

int[][] resArray = new int[res.size()][x];
res.toArray(resArray);
```
^ converts res list to an array
