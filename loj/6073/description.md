
# 题目描述

给定一棵 $ n $ 个点的边带权的树，以及一个排列 $ p $，有 $ q $ 个询问，给定点 $ u, v, k $，设 $ \text{path}(u, v) $ 表示 $ u $ 到 $ v $ 的路径，$ \text{dist}(u, v) $ 表示 $ u $ 到 $ v $ 的距离，希望你求出

$$ \sum\limits_{i \in \text{path}(u, v)} \text{dist}(p_i, k) $$

# 输入格式

第一行一个整数 $ \text{type} $ 表示这个测试点的数据类型。  
第二行两个整数 $ n, q $。  
接下来 $ n - 1 $ 行，每行三个整数 $ u_i, v_i, c_i $，代表树上有一条连接 $ u_i, v_i $ 的权值为 $ c_i $ 的边。  
接下来一行 $ n $ 个正整数表示给定的排列 $ p $。  
接下来 $ q $ 行，每行三个整数 $ u', v', k' $，记 $ \text{lastAns} $ 为上一次询问的答案，假如这是第一次则 $ \text{lastAns} = 0 $，那么这个询问对应的 $ u, v, k $ 满足 $ u = u' \mathbin{\text{xor}} (\text{lastAns} \times \text{type}), v = v' \mathbin{\text{xor}} (\text{lastAns} \times \text{type}), k = k' \mathbin{\text{xor}} (\text{lastAns} \times \text{type}) $。

# 输出格式

输出 $ q $ 行，代表每个询问的答案。

# 样例

#### 样例输入
```plain
0
5 3
1 5 3
1 3 9
1 2 10
1 4 7
1 3 5 2 4
5 4 5
2 3 3
4 3 1
```

#### 样例输出
```plain
26
21
13
```

# 数据范围与提示

对于 $ 20\% $ 的数据，$ n, q \leq 5000 $；  
对于 $ 40\% $ 的数据，$ n, q \leq 50000 $；  
对于另外 $ 10\% $ 的数据，$ p_i = i $；  
对于另外 $ 20\% $ 的数据，$ \text{type} = 0 $；  
对于 $ 100\% $ 的数据，$ 1 \leq n, q \leq 200000; 0 \leq c_i \leq 10 ^ 9; 1 \leq u, v, k \leq n $。

