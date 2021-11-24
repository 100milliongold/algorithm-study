# Tree

## 104. Maximum Depth of Binary Tree

이진 트리의 루트가 주어지면 최대 깊이를 반환합니다.

바이너리 트리의 최대 깊이는 루트 노드에서 가장 먼 리프 노드까지 가장 긴 경로를 따라 있는 노드의 수입니다.

### Example 1:

![image](./tmp-tree.jpeg)

```
Input: root = [3,9,20,null,null,15,7]
Output: 3
```

### Example 2:

```
Input: root = [1,null,2]
Output: 2
```

### Example 3:

```
Input: root = []
Output: 0
```

### Example 4:

```
Input: root = [0]
Output: 1
```


## 100. Same Tree

두 이진 트리 p와 q의 루트가 주어졌을 때 같은지 아닌지 확인하는 함수를 작성하십시오.

두 개의 이진 트리가 구조적으로 동일하고 노드가 동일한 값을 갖는 경우 동일한 것으로 간주됩니다.

### Example 1:

![image](./ex1.jpeg)

```
Input: p = [1,2,3], q = [1,2,3]
Output: true
```

### Example 2:

![image](./ex2.jpeg)

```
Input: p = [1,2], q = [1,null,2]
Output: false
```

## 226. Invert Binary Tree

이진 트리의 루트가 주어지면 트리를 반전하고 루트를 반환합니다.

### Example 1:

![image](./invert1-tree.jpeg)

```
Input: root = [4,2,7,1,3,6,9]
Output: [4,7,2,9,6,3,1]
```


### Example 2:

![image](./invert2-tree.jpeg)

```
Input: root = [2,1,3]
Output: [2,3,1]
```

### Example 3:

```
Input: root = []
Output: []
```


## 124. Binary Tree Maximum Path Sum

이진 트리의 경로는 시퀀스의 각 인접 노드 쌍에 연결하는 가장자리가 있는 노드 시퀀스입니다. 노드는 시퀀스에서 최대 한 번만 나타날 수 있습니다. 경로는 루트를 통과할 필요가 없습니다.

경로의 경로 합은 경로에 있는 노드 값의 합입니다.

이진 트리의 루트가 주어지면 비어 있지 않은 경로의 최대 경로 합계를 반환합니다.

### Example 1:

![image](./exx1.jpeg)

```
Input: root = [1,2,3]
Output: 6
Explanation: The optimal path is 2 -> 1 -> 3 with a path sum of 2 + 1 + 3 = 6.
```



### Example 2:

![image](./exx2.jpeg)

```
Input: root = [-10,9,20,null,null,15,7]
Output: 42
Explanation: The optimal path is 15 -> 20 -> 7 with a path sum of 15 + 20 + 7 = 42.
```

 

Constraints:

- 트리의 노드 수가 범위 내에 있습니다. $${[1, 3*10^4]}$$
- -1000 <= Node.val <= 1000
