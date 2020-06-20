
# Content

[上一集](https://acm.uestc.edu.cn/problem/di-er-zhang-bei-jing-zhi-wang-de-xian-shen/description/) 

# 第三章：向监狱进发

「啊————」糖集中全身的力量，终于把 HeRaNO 打倒了。

HeRaNO 双手扶着剑，单膝跪地。

「不愧是你，居然真的能在如此短的时间内就超越我这么多年的修行。看来 ZXyang 没看错人。」HeRaNO 欣慰地笑了笑。

「什么意思？」 糖歪了歪头，疑惑地问。

HeRaNO 笑了笑：「且听我慢慢和你道来。」

「在[当年](https://acm.uestc.edu.cn/problem/da-di-de-lie-bian/description)，大家都知道 ZXyang 来到 wf (winterfall) 找到了我，并且和我一起修复大地的损伤。但是，鲜有人知的是，当年的我只是一个自私自利的小人，是 ZXyang 先找到并且打败了我，才有今天的我。」

「而他找到我之前，其实是有一位高人找到了他，并且指点他来找我。而[这一部分的故事](https://acm.uestc.edu.cn/problem/ran-shao-de-yuan-zheng/description)就几乎没人知道了。（指趣味赛这题没出成）这位高人 Vingying ，后来与我们成为了队友，一起对抗大地的腐化。本来他也应该被世人所铭记的。」HeRaNO 顿了顿，然后表情开始凝重起来。

「他因为[某些不可言说的原因](https://acm.uestc.edu.cn/problem/kuai-le-shui-tou-yun-ji-hua/description) ， 被抓了起来。从此在大陆的传说中，他的名字就被抹去了。我曾经召集天下的人去[拯救](https://acm.uestc.edu.cn/problem/vingying-ying-jiu-ji-hua/description)他，但是没有一个人成功。」 

![A.png](/source/lutece/di-san-zhang-xiang-jian-yu-jin-fa/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMDMvRVNseDNUS2ROWkc5NDV3LnBuZw==.png)

「我们等了这么久，才等来一个有如此天赋的新人。现在我们把希望寄托给你了。求求你去救救我们的队友 Vingying 吧。今天我便把我的功力传给你。」说罢，HeRaNO 双手一变换，开始对糖传功。

「你可记好了，这一招必须要在理解自动机的基础上才能进行运用。这一个绝招叫做 AC自动机。只要输入你的想法，就可以自动 AC。这个算法可是经历了数代研究，最后才成这样。一定要好好利用！」 HeRaNO 刚说完，便力竭倒下了。

糖看了看倒在地上的两人，下定决心，一定要消灭这些不公，并且救出 Vingying。

----





一个月后，糖来到了中原，偶然见到了她从小玩到大的发小 Fatdog _jo 。

![tenor.gif](/source/lutece/di-san-zhang-xiang-jian-yu-jin-fa/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMDMvTlM3UGJBcWQyeEo1ZVUxLmdpZg==.gif)

 Fatdog _jo 是一个和糖年龄相仿的少年，而糖喜欢称他为狗。狗的天赋虽然不如糖，但是也是一把好手。在跟糖共同修炼了一段时间后，也有了长足的进步。

而即将踏入监狱的他们，决定在进去之前先对练一把。

-----

狗会给出 $n$ 个由小写字母组成的串，并且做出 $q$ 组询问，每次询问对于 $k,m$  两个数，对于 $k$ 对数 $a_i,b_i$ ，表示选取第 $a_i$ 个串长度为 $b_i$ 的前缀放入多重集合 $s$ ，问把多重集合 $s$ 中的所有串分割成 $m$ 个非空多重集合，且使这些多重集合里的串不存在某一个串是另一个串的后缀有多少种方案。

# Standard Input

第一行给出两个数 $n$ , $q$ ，分别代表串数和询问数。
接下来 $n$ 行，每行包含一个字符串
接下来 $q$ 组询问，每组询问第一行输入 $k,m$ 两个数，接下来跟随 $k$ 行
每行有两个数 $a,b$

# Standard Output

每行输出一个数表示答案对 $10^9+7$ 取模后的结果

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
<tr><td>2 3
aabaa
aabaa
4 3
1 2
1 3
1 4
2 5
4 2
2 2
1 3
2 4
1 5
2 2
1 1
1 1</td><td>5
4
1
</td></tr><tr><td>3 2
sugaryongyuandeshen
sugaryongyuandishen
kuaiquguanzhusugar
3 3
1 5
2 5
3 18
6 2
1 1
1 5
2 2
3 14
2 3
3 7</td><td>1
16
</td></tr></table>


# Constraints

$1\leq n,q\leq 10^5,\sum |s| \leq 10^5,\sum k \leq 10^5,m\leq \text{min}(k,300)$
输入保证 $a,b$ 合法

# Note

对于第一组样例的第一次询问的解释：
询问中选择了四个前缀，分别为

第一个串的长度为 2 的前缀：aa

第一个串的长度为 3 的前缀：aab

第一个串的长度为 4 的前缀：aaba

第二个串的长度为 5 的前缀：aabaa

显而易见的，第一个前缀是第四个前缀的后缀，所以这两个串不能放在同一个集合里。所以所有的可能情况有：

{aa},{aabaa},{aab,aaba}

{aa,aab},{aabaa},{aaba}

{aa,aaba},{aabaa},{aab}

{aa},{aabaa,aab},{aaba}

{aa},{aabaa,aaba},{aab}

一共五种。

# Source


