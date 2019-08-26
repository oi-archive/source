
# 题目描述

>一切伟大的世界历史事件与人物，可以说都会出现两次  
>第一次是作为悲剧出现  
>第二次，则是作为笑剧出现  
>——《路易.巴拿马的雾月十八日》  
>感动、  
>痛苦、  
>以及快乐、  
>都只是遥不可及的宝石  
>即便如此，人们啊，  
>获得幸福吧！  
>![zqq1.png](source/loj/6200/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8yMy81Y2JmMGM1OWI0YzFkLnBuZw==.png)  
>世界将在 7 月 20 日终结。  
>世界回归天空的日子。  
>万物被天空侵染的日子。  
>回归天空的日子。  
>世界必须回归。  
>世界的极限。  
>世界的尽头。  
>世界的终结。  
>![zqq2.png](source/loj/6200/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8yMy81Y2JmMGM2MjYxNGNhLnBuZw==.png)  
>你看……那就是极限……最尽头的天空。  
>如今，已无应该之事了如今，已无忘却之物了。  
>不需要的话语。  
>![zqq3.png](source/loj/6200/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8yMy81Y2JmMGM2MWMxMzdlLnBuZw==.png)  
>告别了永不相交的平行，我被吸进了……  
>垂直下落的世界。  
>![zqq4.png](source/loj/6200/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8yMy81Y2JmMGM1ZTIwMzZlLnBuZw==.png)  
>虽哭亦喜  
>虽悲亦喜  
>各种感情混在一起……  
>比起其他所有，想必还是高兴占多吧  
>她高兴地抱着我  
>紧紧地抱着  
>再也不会松开了……  
>想永远这样……  
>她的思绪，以比语言更快的速度，传达给了我  
>有些东西，比语言更快  
>她的思绪，以比语言更快的速度，传达给了我  
>有些东西，比语音更准确  
>世界上无论多么短暂的瞬间，都有意义  
>有意义  
>快临近终结了  
>最后的瞬间  
>啊啊……  
>远方的警笛声  
>黑色的天空  
>月正笑  
>地正润潮  
>星正舞  
>风正凉  
>在我怀中，温暖的，  
>橘希实香  
>![zqq5.png](source/loj/6200/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8yMy81Y2JmMGM1ZWMzYzIyLnBuZw==.png)  
>她在我的怀中……静静地合上了双眼  
>然后我也……  
>静静地合上了双眼

您正在打 galgame，然后突然家长进来了，于是您假装在写数据结构题：

给一个树，$n$ 个点，有点权，初始根是 $1$。

$m$ 个操作，每次操作：

1.	将树根换为 $x$。

2.	给出两个点 $x,y$，从 $x$ 的子树中选每一个点，$y$ 的子树中选每一个点，如果两个点点权相等，$\text{ans}$ 自增 $1$，求 $\text{ans}$。


# 输入格式

第一行两个数表示 $n,m$。

第二行 $n$ 个数，表示每个点的点权 $a_i$。

之后 $n-1$ 行，每行两个数 $x,y$，表示一条边

之后 $m$ 行，每行为 $1$ $x$ 或者 $2$ $x$ $y$。

$1$ $x$，表示将根变成 $x$ 点。

$2$ $x$ $y$，表示查询 $x$ 点的子树与 $y$ 点的子树。


# 输出格式

对于每个询问，输出一个数表示答案。

# 样例

#### 样例输入
```plain
5 5
1 2 3 4 5
1 2
1 3
3 4
3 5
2 4 5
2 1 5
2 3 5
1 5
2 4 5
```
#### 样例输出
```plain
0
1
1
1
```

# 数据范围与提示

$1 \leq n \leq 10^{5},1 \leq m \leq 5 \times 10^{5},1 \leq a_i \leq 10^{9}$



