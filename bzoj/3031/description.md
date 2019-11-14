
# Description

<div class="content"><p><span style="font-size: medium">　　吃过草莓刨冰之后，Vani和cl有些疲倦地坐在一个长椅上。<br/>
　　“呐，玩得开心吗？”Vani忽然问道。<br/>
　　“嗯……很，很开心的说。”<br/>
　　“那么，我有一个问题想要问你呢。”<br/>
　　cl的脸有点红了起来。<br/>
　　“嗯……好吧。问、问吧……我会告诉你的哦……”<br/>
　　“那好。对于一个分数A / B……”<br/>
　　“嗯……哎？哎？！”<br/>
　　“……就是这个问题。我觉得这个问题好纠结啊……”<br/>
　　Vani淡定地说完这句话。<br/>
　　“啊？！哈啊？！” </span></p>
<p><span style="font-size: medium">　　对于给定的分数 A / B，求其在 K 进制下是有限小数还是循环小数。如果是有限小数，求小数点后的位数；如果是循环小数，则求混循环部分和循环节的长度又分别是多少。<br/>
　　注意，循环节指的是最短循环节，且混循环部分的长度也指最短。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">　　第一行一个正整数 T，表示测试数据的数目。<br/>
　　每个测试数据包含三个空格分隔的整数 A, B, K。含义如题目所示。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">　　对于每个测试数据，在单独的一行内输出两个空格分隔的整数 M, R。<br/>
　　其中 M 表示混循环部分的长度，R 表示循环节的长度。<br/>
　　如果 A / B 在 K 进制下是有限小数，则 R = 0，M 为小数点后面的位数；如果 A / B 在 K 进制下是纯循环小数，则 M = 0。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 8 10<br/>
17 99 10<br/>
217 990 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 0<br/>
0 2<br/>
1 2</span></div>

# Hint

<div class="content"><p></p><p>　对于 100% 的数据，1≤A&lt;B≤10^12，K≤10^12，T≤10。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize2">Poetize2</a></p></div>

