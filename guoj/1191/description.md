
# 题目描述

16 世纪法国外交家 Blaise de Vigenère 设计了一种多表密码加密算法——Vigenère 密码。Vigenère 密码的加密解密算法简单易用，且破译难度比较高，曾在美国南北战争中为南军所广泛使用。

在密码学中，我们称需要加密的信息为明文，用 $M$ 表示；称加密后的信息为密文，用 $C$ 表示；而密钥是一种参数，是将明文转换为密文或将密文转换为明文的算法中输入的数据，记为 $K$。在 Vigenère 密码中，密钥 $K$ 是一个字符串，$K = k_1k_2 \dots k_n$。当明文 $M = m_1m_2 \dots m_n$ 时，得到的密文 $C = c_1c_2 \dots c_n$，其中 $c_i = m_i \mathbin{®} k_i$，运算 $®$ 的规则如下表所示： 

![如图片失效请下载附加文件](/source/guoj/1191/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNjAyL3Rlc3RkYXRhL2Rvd25sb2FkL3ZpZ2VuZXJlLnBuZw==.png)

Vigenère 加密在操作时需要注意：

1. $®$ 运算忽略参与运算的字母的大小写，并保持字母在明文 $M$ 中的大小写形式；
2. 当明文 $M$ 的长度大于密钥 $K$ 的长度时，将密钥 $K$ 重复使用。

例如，明文 $M = \texttt{Helloworld}$，密钥 $K = \texttt{abc}$ 时，密文 $C = \texttt{Hfnlpyosnd}$。

| 明文 | H | e | l | l | o | w | o | r | l | d |
|------|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|
| 密钥 | a | b | c | a | b | c | a | b | c | a |
| 密文 | H | f | n | l | p | y | o | s | n | d |


# 输入格式

第一行为一个字符串，表示密钥 $K$，长度不超过 $100$，其中仅包含大小写字母。

第二行为一个字符串，表示经加密后的密文，长度不超过 $1\,000$，其中仅包含大小写字母。

# 输出格式

输出共 $1$ 行，一个字符串，表示输入密钥和密文所对应的明文。

# 样例

#### 样例输入 1
```plainplain
CompleteVictory
Yvqgpxaimmklongnzfwpvxmniytm
```

#### 样例输出 1
```plainplain
Wherethereisawillthereisaway
```

# 数据范围与提示

对于 100% 的数据，输入的密钥的长度不超过 $100$，输入的密文的长度不超过 $1\,000$，且都仅包含大小写字母。

