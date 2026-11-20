# Prim's Algorithm

A C++ implementation of Prim's algorithm that constructs a minimum spanning tree from an adjacency matrix.

## Complexity

- Time: `O(V^2)`
- Space: `O(V)`

## Compile

```bash
g++ prims.cpp -o prims
```

## Run

```bash
./prims
```

Enter the number of vertices followed by the adjacency matrix. Use `0` for no edge.

```text
4
0 10 6 5
10 0 0 15
6 0 0 4
5 15 4 0
```