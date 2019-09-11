# 题目描述


<h3>
【问题描述】
</h3>
<p>
<br/>
在LazyCat同学的影响下，Roby同学开始听韩国的音乐，并且越来越喜欢H.o.T，尤其喜欢安七炫和Tony，可是，爱学习爱思考的Roby同学想，如果以后喜欢的韩星越来越多怎么办呢？Roby怎么知道Roby最喜欢谁呢（Roby都不知道谁知道呢。。。。）？ <br/>
于是，Roby同学求助于你。 <br/>
Roby首先会给你一张表，表上是所有他认识的韩星的名字，一开始他对所有韩星的好感度都为0。 <br/>
然后Roby会告诉你一些他对某个韩星的好感度变化。 <br/>
最后，请按照Roby对他们好感从大到小的顺序输出他们。
</p>
<p>
[输入] <br/>
第一行一个个数N，表示Roby知道的韩星数目。 <br/>
后面有N行，表示每一个Roby认识的韩星的名字。 <br/>
再下面一行一个数K。 <br/>
接下来2*K行，每两行为一组，上面一行为韩星的名字Name，下面一行为好感度变化量Change。
</p>
<p>
[输出] <br/>
N*2行，依据韩星们的受Roby好感度从大到小的顺序输出，每两行为一组，第一行输出韩星的名字，第二行输出受Roby的好感度。
</p>
<p>
[样例输入] <br/>
3 <br/>
HhIsaGay <br/>
ZcLoveStudy <br/>
OneBlueOne <br/>
5 <br/>
ZcLoveStudy <br/>
100 <br/>
OneBlueOne <br/>
8888 <br/>
ZcLoveStudy <br/>
20 <br/>
OneBlueOne <br/>
8888 <br/>
HhIsaGay <br/>
-1000
</p>
<p>
<br/>
[样例输出] <br/>
OneBlueOne <br/>
17776 <br/>
ZcLoveStudy <br/>
120 <br/>
HhIsaGay <br/>
-1000
</p>
<p>
[数据范围] <br/>
对于20%的数据，保证N&lt;=100，K&lt;=100. <br/>
对于40%的数据，保证N&lt;=10000，K&lt;=30000. <br/>
对于100%的数据，保证N&lt;=100000　-8888&lt;=Change&lt;=8888　K&lt;=100000.
</p>
<p>
[时限] <br/>
2S
</p>
