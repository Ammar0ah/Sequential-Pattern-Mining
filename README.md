# Sequential-Pattern-Mining
### An implementation of PrefixSpan Algorithm for Sequence Pattern Mining

Input:
```
prefixSpan(alpha="",dataset=[
[["a"], ["a", "b", "c"], ["a", "c"], ["c"]],
[["a"], ["c"], ["b", "c"]],
[["a", "b"], ["d"], ["c"], ["b"], ["c"]],
[["a"], ["c"], ["b"], ["c"]]
],min_sup=2)

```
Output: 
```
['a,: 4',
 'a,b,: 4',
 'a,b,c,: 3',
 'a,b,c,c,: 2',
 'a,c,: 4',
 'a,c,c,: 4',
 'a,c,b,: 2',
 'b,: 4',
 'b,b,: 4',
 'b,c,: 4',
 'c,: 4',
 'c,b,: 4',
 'c,c,: 4']
```
