### 题意

给一个长度为 $N$ 的非负整数序列 $S=s_{1},s_{2},... ,s_{N}$  和一个整数 $K$。求满足以下条件的 $S$ 的**最长**连续子序列的长度。

- 该子序列中所有元素的值的乘积小于或等于 $K$。 

子序列的长度必须大于或等于 $1$。
如果没有一个子列满足条件，则输出 $0$。

### 数据范围

$1 \leq N \leq 10^5,1 \leq K,s_{i} \leq 10^9$

---

### 输入格式

```
N K
s1
s2
:
sN
```

### 输出格式

一行一个数，表示最长连续子序列的长度。

---

### 样例输入1

```
7 6
4
3
1
1
2
10
2
```

### 样例输出1

```
4
```

### 样例解释1

子序列 $S[2...5]=s_{2},s_{3},s_{4},s_{5}$  被选中，积为 $3\times 1\times 1\times 2=6$，小于或等于 $K$。

---

### 样例输入2

```
6 10
10
10
10
10
0
10
```

### 样例输出2

```
6
```

---

### 样例输入3

```
6 9
10
10
10
10
10
10
```

### 样例输出3

```
0
```

---

### 样例输入4

```
4 0
1
2
3
4
```

### 样例输出4

```
0
```
