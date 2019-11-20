
# 题目描述

作为一个签到题，这题就不写题面了。

有一个长度为 $n$ 的数组 $a_0,a_1 \cdots a_{n-1}$，其中 $n$ 为 $2$ 的次幂。

你要处理以下五种操作：

1. `add x y`：把 $a_x$ 增加 $y$。
2. `sum x y`：求出 $\sum_{i=x}^y a_i$。
3. `and x`：执行以下操作：
```cpp
for(int i=0;i<n;++i) b[i]=0;
for(int i=0;i<n;++i) b[i&x]+=a[i];
for(int i=0;i<n;++i) a[i]=b[i];
```
4. `or x`：执行以下操作：
```cpp
for(int i=0;i<n;++i) b[i]=0;
for(int i=0;i<n;++i) b[i|x]+=a[i];
for(int i=0;i<n;++i) a[i]=b[i];
```
5. `xor x`：执行以下操作：
```cpp
for(int i=0;i<n;++i) b[i]=0;
for(int i=0;i<n;++i) b[i^x]+=a[i];
for(int i=0;i<n;++i) a[i]=b[i];
```

# 输入格式

第一行两个正整数 $n,q$，表示序列长度和操作数量。

第二行 $n$ 个正整数 $a_0,a_1 \cdots a_{n-1}$，为 $a$ 数组的初始值。

接下来 $q$ 行每行形如：

1. `add x y`
2. `sum l r`
3. `and x`
4. `or x`
5. `xor x`

# 输出格式

对于每个 `sum` 操作输出一行，表示所求的和。

# 样例

#### 样例输入1
```
4 5
1 0 1 0
add 3 1
and 2
xor 1
sum 3 3
sum 0 3
```

#### 样例输出1
```
2
3
```

# 数据范围与提示

对于所有数据，$1 \leq n,q \leq 524288$，$0 \leq x \leq n-1$，$0 \leq l \leq r \leq n-1$，$0 \leq a_i,y \leq 10^9$，$n$ 为 $2$ 的次幂。

Subtask 1（20pts）：$n,q \leq 128$。

Subtask 2（30pts）：$n,q \leq 131072$。

Subtask 3（20pts）：$n=q=524288$，对于每个询问操作先随机选择五种中的一种，其余参数均在数据范围内均匀随机。

Subtask 4（30pts）：无特殊限制。

测了一下发现标程没加读入优化也都在时限一半以内，今天就不发 `io.cpp` 了

命题人：fjzzq2002

