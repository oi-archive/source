
# 题目描述

Yazid 喜欢吃大碗宽面。现有 $m$ 碗宽面，其中第 $i$ 碗宽面（$1\leq i\leq m$）共包含 $n_i$ 根面条，它们的宽度分别为 $A_{\large i,1},A_{\large i,2},\dots A_{\large i,n_{\large i}}$。

记 $f(u,v)$ 表示若混合第 $u$ 碗宽面和第 $v$ 碗宽面，将得到的超大碗宽面的**第 $\left\lfloor\frac{n_u +n_v +1}{2}\right\rfloor$ 小**的面条宽度（$\lfloor x\rfloor$ 表示不超过 $x$ 的最大整数）。

Yazid 想求出所有 $f(u,v)$，但为了节省你的输出时间，你只需要对所有 $1\leq u\leq m$ 求出：

* $R(u)=\mathop{\rm xor}\limits_{v=1}^{m} {(f(u,v)+u+v)}$（$\mathrm{xor}$ 指异或运算，在 C++ 语言中对应 $\large{\tt{\text{^}}}$ 运算符）。


# 输入格式

第一行一个正整数 $m$，表示宽面碗数。

接下来 $m$ 行，每行若干个用单个空格隔开的整数描述一碗宽面：这部分的第 $i$ 行的第一个正整数为 $n_i$，表示第 $i$ 碗宽面包含的面条数；接下来 $n_i$ 个非负整数 $A_{i,1},A_{i,2},\dots A_{i,n_i}$ 描述各面条的宽度。

保证 $m\leq 10000$，$n_i\leq 500$，$0\leq A_{i,j}\leq 10^9$。

# 输出格式

输出 $n$ 行，每行一个整数，其中第 $i$ 行的整数为 $R\left(i\right)$。

# 样例

##### 样例输入 1

```plain
3
3 1 2 3
3 3 4 5
2 4 2
```

##### 样例输出 1

```plain
4
7
7
```

##### 样例说明 1

$\def\x{\operatorname{xor}} R(1) = {(f(1,1)+2)}\x{(f(1,2)+3)}\x{(f(1,3)+4)} = 4\x6\x6 = 4$  
$\def\x{\operatorname{xor}} R(2) = {(f(2,1)+3)}\x{(f(2,2)+4)}\x{(f(2,3)+5)} = 6\x8\x9 = 7$  
$\def\x{\operatorname{xor}} R(3) = {(f(3,1)+4)}\x{(f(3,2)+5)}\x{(f(3,3)+6)} = 6\x9\x8 = 7$

<!--$R\left(1\right)=\left(f\left(1,1\right)+2\right) xor \left(f\left(1,2\right)+3\right) xor \left(f\left(1,3\right)+4\right)=4\mathrm{ \, xor\, }6\mathrm{ \, xor\, }6=4$  
$R\left(2\right)=\left(f\left(2,1\right)+3\right) xor \left(f\left(2,2\right)+4\right) xor \left(f\left(2,3\right)+5\right)=6\mathrm{ \, xor\, }8\mathrm{ \, xor\, }9=7$  
$R\left(3\right)=\left(f\left(3,1\right)+4\right) xor \left(f\left(3,2\right)+5\right) xor \left(f\left(3,3\right)+6\right)=6\mathrm{ \, xor\, }9\mathrm{ \, xor\, }8=7$>

# 数据范围与提示

来自 THUPC（THU Programming Contest，清华大学程序设计竞赛）2019。

题解等资源可在 https://github.com/wangyurzee7/THUPC2019 查看。

