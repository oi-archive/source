
# 题目描述

wjyyy 安排过去了考试之后，又收到了一本作业，不过他所在的班级准备通力合作。

wjyyy 的班级有 $2^n$ 个人，他们的编号为 $1\sim 2^n$，由第 $1$ 个人开始拿一本空作业开始写。

作业共有 $n$ 面。每个人可以选择**已经写过的一面**把这一面**擦掉**；也可以选择**空的一面**把这一面**写完**。第 $i$ 个人写完后，第 $i+1$ 个人会拿到一本与第 $i$ 个人写完后一模一样的作业。每个人能且只能改变 $n$ 面作业中一面的状态，同时，他们不想让任何两个人的作业相同。

由于他们都在写作业，所以让你来帮他们解决这个问题。

你需要依次输出每个同学的作业写完后的状态，用一个 $n$ 位二进制数表示。它的第 $i$ 位为 $1$ 表示第 $i+1$ 面是有答案的；为 $0$ 表示第 $i+1$ 位是空的。即 $0$ 代表初始状态。

如果有多种方案，输出任意一种都算正确。

# 输入格式

输入一行一个正整数 $n$。

# 输出格式

输出一行 $2^n$ 个非负整数，第 $i$ 个非负整数表示十进制下第 $i$ 个同学写完作业后作业的状态。

# 样例

#### 样例 1 输入
```plain
2
```

#### 样例 1 输出
```plain
1 3 2 0
```

#### 样例 1 解释

样例解释中的作业状态用二进制表示。

|编号|写完后的作业|
|:-:|:-:|
|$1$|$10$|
|$2$|$11$|
|$3$|$01$|
|$4$|$00$|

# 数据范围与提示

子任务 $1(1pts)$：$n\le 2$，  
子任务 $2(15pts)$：$n\le 4$，  
子任务 $3(30pts)$：$n\le 10$，  
子任务 $4(54pts)$：$n\le 22$。

对于 $100\%$ 的数据，$1\le n\le 22$。

**注意：GuOJ 的代码长度限制为 100KB。**

