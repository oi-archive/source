
# Content

喜びと幸せの記憶 取り戻すように
为了重拾过往喜悦与幸福的记忆
誰もが皆 捜し求め 手を伸ばす光
人们纷纷伸出双手寻求光芒

どこまでも続く 終わりなき日々に
在连绵不断永无休止的岁月里
惜しみなく この身 預けて
毫不吝啬地托付出这副身躯

荒れ狂う波に 浮かぶ花のように
如同在怒涛中沉浮的花儿
Lead the way 嵐を乗り越えて
乘风破浪 跨越这场暴风雨

枯れ行く大地を 踏みしめるように
宛如稳踏在洪水退去的大地上
Go ahead 真っ直ぐ歩みだせる
从此开始 勇往直前吧

——《[Resuscitated Hope](https://music.163.com/song?id=600347)》

---

~~半吊子秀才~~久城最近学到了幂运算，但是没有弄明白。所以他去问了维多利加。

为了测试久城是否真的学会了，维多利加准备了一个长度为 $n$ 的数列 $\{a_n\}$。

她会问久城 $q$ 个问题，每个问题都会给出三个参数 $l,r,m$。对于每个问题，她都需要久城回答如下式子的值：

$$
f(a_l,f(a_{l+1},f(a_{l+2},\ldots f(a_{r-2},f(a_{r-1},a_r))\ldots )))\bmod m
$$

其中 $f(a,b)=a^b$。

久城只会基础的幂次求值，回答不出来维多利加的问题。

你是一个一般经过的路人，看到这道题后你想帮帮久城，作为回报狗粮管饱。

# Standard Input

第一行两个整数 $n,q$，意义如题目描述；

第二行 $n$ 个整数，表示这个数列 $\{a_n\}$；

接下来 $q$ 行，每行三个整数 $l,r,m$，意义如题目描述。

# Standard Output

输出 $q$ 行，每行一个整数，表示对应问题的答案。

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
<tr><td>6 3
1 1 4 5 1 4
1 6 1919810
3 4 19
4 6 5</td><td>1
17
0</td></tr></table>


# Constraints

$2\le n,q\le 2\times 10^5,1\le l< r\le n,1\le a_i,m\le 10^7$

# Note

样例一中，对于第一个询问：

$$
f(1,f(1,f(4,f(5,f(1,4)))))\equiv 1\pmod {1919810}
$$

对于第二个询问：

$$
f(4,5)\bmod 19=1024\bmod 19=17
$$

对于第三个询问：

$$
f(5,f(1,4))\bmod 5=5\bmod 5=0
$$

# Source


