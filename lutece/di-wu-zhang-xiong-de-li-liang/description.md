
# Content

[上一集](https://acm.uestc.edu.cn/problem/di-si-zhang-bu-yao-ting-xia-lai-a/description)

# 第五章：熊的力量

「咳。。。。」詹皇看了看旁边已然昏迷的兔和马。

「不打了不打了，打不过你。」詹皇笑了笑，「你不是就只是想要那个小舔狗吗？我也没杀了他，还给你吧。」詹皇手轻挥，空间骤然开始波动。其中出现了一道深不见底的裂缝，而狗的一只手漏了出来。

糖立马顾不得自己现在的狼狈样子，抓住了狗的手。

「**这次，我不会再让你离开我。**」

![OIP.jpg](/source/lutece/di-wu-zhang-xiong-de-li-liang/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMDQvdEliTXJMZTdtaFNEUk80LmpwZw==.jpg)

詹皇微笑着坐在地上，开始讲起了自己以前的故事。

「曾经，我也是一个纯真的少年，心里只想着在区域码力大会上取得好成绩。。。」

![pic](/source/lutece/di-wu-zhang-xiong-de-li-liang/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMTcvVnNvSVd5VVpSQk9TdDU2LmpwZw==.jpg)

「但是，经过某些事情之后。。。。我黑化了。。。。」（指头像黑化）

![收到.png](/source/lutece/di-wu-zhang-xiong-de-li-liang/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMDQvOXBxOEtJZWNnNWZhRXdyLnBuZw==.png)

「甚至活成了我曾经最讨厌的样子」

![不准.png](/source/lutece/di-wu-zhang-xiong-de-li-liang/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMDQveHpQcE1pNEpLSXFHdHZRLnBuZw==.png)

「但是我在你的身上看到了希望。去吧，去监狱的深处。找到把守最后一关的 forgottencsc ，我们尊称他为熊。你只有打败他，才有可能达成你的目的。」

![熊.png](/source/lutece/di-wu-zhang-xiong-de-li-liang/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMDQvOWRhclQ3SHp1UDZRMXRZLnBuZw==.png)

「我只说这么多了。。。成败与否看你自己了。我在你身上看到了我当年的影子。这几个人就由我来照顾吧。」詹皇看向糖，一幅欣然的表情。

虽然糖仍然不是很相信詹皇，但是之前的结果是狗确实还好好的活着，想必詹皇并没有理由结束狗的性命。眼下唯一的选择是自己一个人去挑战熊。

「我知道了，我会在救出人之后就回来找你。」

----

金色的码力，糖第一次看到这样澄澈的码力。但是，自己的码力也不会输。

「你不应该想着要把他放出来。你绝对会后悔的。我[当年](https://acm.uestc.edu.cn/contest/27/summary)曾经独步天下，现在却只是在这守门，就是为了守住他。」 熊目视着糖，眼神平静。

糖没有说话，只是兀自运起了码力。

「好吧，我这么多年打退了这么多人，你也会是下一个。看你这样子也是略懂字符串。 你应该也知道 AC自动机是离线算法，那么我今天就要让他在线一回！」 熊变换双手，手中竟然出现了一个集合。集合中的字符井然有序，排列成了字符串的形状。

只见那集合中的字符串进进出出，字符看似乱码，却好像又有某种规律。

「听好了！我现在要你维护一个集合，支持插入和删除。」 熊大声呵斥。

糖一听，便心里有了个打底的想法。

「看你这样子，大概已经想到如何离线了吧。但是，今天我便要把他加密。」

「加密？」糖惊讶地说。

熊冷笑了一下：「我今天就要强制在线。对于每一次输入的字符串 $s$ 必须进行以下处理：」

```c++
int n = strlen(s);
for( int i = 0 ; i < n ; i++ )
{
    s[i] = (( s[i] - 'a' ) + lastans * i % 26 ) % 26 + 'a';
}
```

其中变量 $lastans$ 为上次询问 3 的答案， $lastans$ 在最初的时候应该为 $0$。

维护一个字符串多重集，支持三种操作：
1.插入**一个**字符串
2.删除**一个**字符串
3.给出一个待匹配串，询问对于多重集内所有元素，所有的元素在待匹配串中匹配次数乘元素串长的和。

糖一听，便有了打算。

# Standard Input

第一行有 $1$ 个数 $n$ ，代表接下来输入的字符串数量。
第二行到第 $n+1$ 行，每行先输入一个数 $op$ ，代表操作种类。接下来输入一个字符串 $s$。

# Standard Output

对于每个询问 3 输出一行一个数代表答案对 $10^9+7$ 取模之后的值。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>7
1 ab
1 abb
1 aabb
3 aabb
2 arja
2 asj
3 asiar
</td><td>9
4
</td></tr><tr><td>10
1 sugar
1 sugari
1 sugarii
1 sugariii
1 sugariv
3 sugariiisugari
2 sjktz
1 sjktzf
1 sjktzf
3 sjktzfuty
</td><td>37
25
</td></tr></table>


# Constraints

$n\leq 3\times10^5,\sum |s| \leq 3\times10^5$
输入保证对于每个操作 $2$ ，在多重集中至少存在一个相同的字符串 $s$ 。

# Note

第一个样例的原输入为：
7
1 ab
1 abb
1 aabb
3 aabb
2 aabb
2 abb
3 ababb

第二个样例的原输入为：
10
1 sugar
1 sugari
1 sugarii
1 sugariii
1 sugariv
3 sugariiisugari
2 sugar
1 sugari
1 sugari
3 sugariisi

# Source


