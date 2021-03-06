
# 题目描述

**译自 [ROI 2019](http://neerc.ifmo.ru/school/archive/2018-2019.html) Day2 T2.** ***[Классные парты](http://neerc.ifmo.ru/school/archive/2018-2019/ru-olymp-roi-2019-day2.pdf)***

有 $m$ 个班，每个班有 $2n$ 名学生。各班将轮流来到一个会议室上课，每次只有一个班在会议室。  
你需要给会议室购买 $n$ 张双人课桌。  
供你选择的课桌分为 $k$ 类，分别编为 $1\ldots k$ 号，$i$ 号课桌适合身高在 $L_i$ 到 $R_i$ 之间的学生。  
学生使用太高或太矮的课桌会感到不适，这可用「不适指数」表示，具体来说：

* 对于身高在这一区间内的学生，其不适指数为 0；
* 对于身高小于 $L_i$ 的学生，设身高为 $h$，则其不适指数为 $L_i-h$；
* 对于身高大于 $R_i$ 的学生，设身高为 $h$，则其不适指数为 $h-R_i$。 

请求出：在课桌最合适的情况下，这 $2mn$ 名学生的不适指数的最小值。

# 输入格式

$m,n,k$  
接下来 $k$ 行：$L_i, R_i$  
接下来 $m$ 行，每行 $2n$ 个整数，表示一个班的每个学生的身高。

# 输出格式



# 样例

#### 样例输入 1
```plain
1 2 2
5 25
50 90
60 5 10 40
```

#### 样例输出 1
```plain
10
```

#### 样例说明 1
第 4 个小朋友的不适指数为 10，其他小朋友为 0.

#### 样例输入 2
```plain
2 3 3
200 400
300 500
100 600
300 330 440 40 30 300
150 250 350 450 550 300
```

#### 样例输出 2
```plain
130
```

#### 样例输入 3
```plain
1 3 4
10 100
200 200
10 100
300 1000
5 10 20 15 200 90
```

#### 样例输出 3
```plain
105
```

# 数据范围与提示

$1 ⩽ m, n ⩽ 2\times 10^5$; $1 ⩽ m · n ⩽ 2\times 10^5$; $2 ⩽ k ⩽ 2\times 10^5$; $1 ⩽ L_i ⩽ R_i ⩽ 10^9$; $1 ⩽$ 学生身高 $⩽ 10^9$.

|子任务 #|分值|$m$|$n$|$k$|额外条件|
|:--:|:--:|:--:|:--:|:--:|:--:|
|1|10|$m ⩽ 100$|$n = 1$|$k ⩽ 50$||
|2|10$$|$m = 1$|$n ⩽ 1000$|$k ⩽ 50$||
|3|10|$m ⩽ 50$|$n ⩽ 5$|$k ⩽ 3$||
|4|10$$|$m ⩽ 100$|$n ⩽ 1000$|$k = 2$||
|5|10|$m ⩽ 100$|$n ⩽ 1000$|$k ⩽ 3$||
|6|10$$|$m ⩽ 100$|$n ⩽ 1000$|$k ⩽ 50$||
|7|10|$m ⩽ 100$|$n ⩽ 1000$|$k ⩽ 50$||
|8|8$$||||$L_i = R_i$|
|9|8|$m ⩽ 100$||||
|10|10$$||$n ⩽ 100$|||
|11|4|||||


