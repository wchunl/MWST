# Minimum Weight Spanning Tree
A python program to determine a minimum weight spanning tree using Kruskal's Algorithm

## Usage

```console
$ python3 mwst.py [input] [output]
```

`input` is a file containing information about a graph. The number of vertices is given in the first line, the number of edges is given in the second line, and the rest of the lines contains two integers which are the two vertices of an edge and a real number which is the weight of the edge. 


`output` is a file containing information about the minimum weight spanning tree. Each vertex and its respective weight of the resulting tree is given along with the label (from which line of the input file it came from) and the total weight of the spanning tree.

## Example

in1:
```console
7
11
1 2 6
1 4 3
2 3 5
2 5 8
3 5 1
3 7 4
4 5 7
4 6 9
5 6 6
5 7 5
6 7 2
```

out1:
```console
   5: (3, 5) 1.0
  11: (6, 7) 2.0
   2: (1, 4) 3.0
   6: (3, 7) 4.0
   3: (2, 3) 5.0
   1: (1, 2) 6.0
Total Weight = 21.00
```