
# 题目描述

为了效仿一些雷同的情况，4qwerty7 竟然决定再出一个 DESede 加密密文解密的题目！

参考资料：

1. Java API 文档

    * <https://resource.seucpc.club/javadocs/api/java/util/Base64.html>(内网访问)
    * <https://resource.seucpc.club/javadocs/api/javax/crypto/package-summary.html>(内网访问)

2. 3DES 简介

    3DES 算法加解密过程分别是对明文/密文数据进行三次 DES 加密或解密，得到相应的密文或明文。假设 $EK$ 和 $DK$ 分别表示 DES 的加密和解密函数，$P$ 表示明文，$C$ 表示密文，那么加解密的方法如下：

    * 加密：$C = EK_3(DK_2(EK_1(P)))$ 即对明文数据进行，加密 -> 解密 -> 加密的过程，最后得到密文数据。
    * 解密：$P = DK_1(EK_2(DK_3(C)))$ 即对密文数据进行，解密 -> 加密 -> 解密的过程，最后得到明文数据。

3. DES 简介

    * (比赛结束后失效)

4. Base64 简介

    Base64 编码即将原来的二进制内容看作来看作 $256$ 进制（每比特内容），然后转换为 $64$ 进制，$0\sim 63$ 分别用如下字符表示：`A、B、C、D、E、F、G、H、I、J、K、L、M、N、O、P、Q、R、S、T、U、V、W、X、Y、Z、a、b、c、d、e、f、g、h、i、j、k、l、m、n、o、p、q、r、s、t、u、v、w、x、y、z、+、/`。

4. ECB 简介

    将明文分成需求数目段，每段分别加密。

5. PKCS5Padding 简介

    计算 $8 - (l\ mod\ 8)$ 的值，$l$ 为文本内容长度，内容末尾填充这个值次这个值。



# 输入格式

首行一个数字 $T(1\leq T\leq 100)$，表示测试数据数目。

每个数据，给定一个字符串，为 DESede/ECB/PKCS5Padding 加密(密钥为 `SEUSCC2019_FINAL_CONTEST`)后经 Base64 编码的内容。

# 输出格式

对于每组数据，给出一行一个解密后的内容，数据保证该内容仅由字母、数字、下划线与感叹号组成，且长度不超过 $384$ 位。

# 样例

#### 输入样例

```plain
1
9kNngqJ7t15RbdxmDPzPlapsWgmupeySTpdRRMEgUZ5PRSU9Njkm1XzlgYVfuDHk
```

#### 输出样例

```plain
Use_Java_to_solve_this_problem_is_easist!
```

# 数据范围与提示



