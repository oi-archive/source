
# 题目描述

这是一道模板题。

给由 $ n $ 个数组成的一个可重集 $ S $，求一个集合 $ T \subseteq S $，使 $ T_1 \mathbin{\text{xor}} T_2 \mathbin{\text{xor}} \ldots \mathbin{\text{xor}} T_{|T|} $ 最大。

# 输入格式

第一行一个数 $ n $。  
第二行 $ n $ 个数，表示集合 $ S $。

# 输出格式

$ T_1 \mathbin{\text{xor}} T_2 \mathbin{\text{xor}} \ldots \mathbin{\text{xor}} T_{|T|} $ 的最大值。

# 样例

#### 样例输入
```plain
3
5 2 8
```

#### 样例输出
```plain
15
```

# 数据范围与提示

$ 1 \leq n \leq 50, 0 \leq S_i \leq 2 ^ {50} $

