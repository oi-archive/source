
# 题目描述

给定一个长度为 $ n $ 的字符串 $ s $，有 $ q $ 组询问，每个询问给定 $ l, r $，询问 $ s[l \ldots r] $ 中有多少本质不同的回文子串。

# 输入格式

第一行一个整数 $ \text{type} $，若 $ \text{type} = 0 $，表示这个数据没有进行加密，若 $ \text{type} = 1 $，表示这个数据进行了加密。  
第二行两个整数 $ n, q $。  
第三行一个字符串 $ s $。  
接下来 $ q $ 行，每行两个整数 $ l', r' $。记 $ \text{lastAns} $ 为上一次询问的答案，若这是第一次询问，$ \text{lastAns} = 0 $，则这次猜测的 $ l, r $ 为 $ l = l' \mathbin{\text{xor}} (\text{type} \times \text{lastAns}), r = r' \mathbin{\text{xor}} (\text{type} \times \text{lastAns}) $。

# 输出格式

输出共 $ q $ 行，代表每个询问的答案。

# 样例

#### 样例输入
```plain
1
8 4
abbabbba
1 7
3 2
6 10
1 0
```

#### 样例输出
```plain
7
2
5
2
```

# 数据范围与提示

对于所有数据，$n\le 100000,q\le 2n$，解密后 $1\le l\le r\le n$，字符串字符集为小写英文字母。

对于 $ 5\% $ 的数据，$ n \leq 100; \text{type} = 1 $；  
对于另外 $ 15\% $ 的数据，$ n \leq 1000; \text{type} = 1 $；  
对于另外 $ 15\% $ 的数据，$ n \leq 30000; \text{type} = 0 $；  
对于另外 $ 15\% $ 的数据，$ n \leq 100000; \text{type} = 0 $；  
对于另外 $ 50\% $ 的数据，$ n \leq 100000; \text{type} = 1 $。

