
# 题目描述

4qwerty7 不知从哪学来 AES 算法，现在你要对一个加密文本进行解密。

# 输入格式

首行一个数字 $T(1\leq T\leq 5)$，表示测试数据数目。

每个数据，给定一个字符串，为 AES-128/CBC/PKCS5Padding 加密(密钥与 iv 为 `SEUSCC2019_FIRST` )后经 Base64 编码的内容。

参考资料：<https://www.cnblogs.com/block2016/p/5596676.html>

# 输出格式

对于每组数据，给出一行一个解密后的内容，数据保证该内容仅由字母数字与感叹号、空格组成，且长度不超过 $100$ 位。

# 样例

#### 输入样例

```plain
1
DwigHE5oeOu2aIAQEzSiwA==
```

#### 输出样例

```plain
Hello world!
```


# 数据范围与提示



