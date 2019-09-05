# 题目描述


<h3>
【题目描述】
</h3>
<p>
从前有两个国家，为避免牵扯到现实，不妨称其为A 国和B 国。B 国是个富
</p>
<p>
强的大国，而A国是个衰落的小国。B 国对A 国虎视眈眈已久，终于在某一天，
</p>
<p>
对A国发起了侵略。
</p>
<p>
A国有n 个城市，某些城市之间有道路相连，道路可以双向通行。设第i 条
</p>
<p>
道路的长度为li ，所有人——不管是A 国的市民还是B 国的侵略军——都需要花
</p>
<p>
费li 个单位时间通过这条道路。任意两个A 国的城市之间有且只有一条互达的路
</p>
<p>
径，也就是说， A国的道路网络构成一棵树。
</p>
<p>
不妨把A国的城市编号为1 ~ n，并把A国的首都编号为1号。我们定义“边
</p>
<p>
界城市”为，以首都为根时，为叶子节点的城市。显然，这些城市会首当其冲地
</p>
<p>
受到侵略。
</p>
<p>
B 国也的确是这么打算的。作为侵略计划的第一步，B 国直接占领了A 国的
</p>
<p>
所有边界城市。我们从这个时刻开始计时，记这个时刻为时刻0 。B 国拥有特别
</p>
<p>
的训练技巧，可以把A 国每个被占领的城市当做自己侵略军的训练营。A 国每个
</p>
<p>
被占领的城市每个单位时间可以训练出一个士兵。假如某城市在时刻x 被占领，
</p>
<p>
这个城市在每个时刻x+i(i&gt;=1)都会训练出一个士兵。
</p>
<p>
B 国侵略计划的第二步是，从边界城市出发，不断把包围网向内缩进，直到
</p>
<p>
占领所有城市。因此，所有士兵都只会朝着首都的方向移动。当然，他们只能沿
</p>
<p>
着城市间的道路移动。
</p>
<p>
A国也不会束手就擒。在每个非边界城市中， A 国都有驻兵把守，城市i 中
</p>
<p>
有di个卫兵。当B 国的士兵进入一个有卫兵驻守的城市时，他会即时与一名卫兵
</p>
<p>
展开战斗，并瞬秒掉那名不幸的卫兵。换言之，我们可以认为一名士兵进入一个
</p>
<p>
城市时，卫兵数量就会减少1（如果还有卫兵的话）。而当一个城市中没有卫兵了
</p>
<p>
之后，这个城市就被B 国占领了，也就可以为B 国训练士兵了。
</p>
<p>
而B 国的士兵也比较奇怪，不会在同一个城市虐两个卫兵。也就是说设定是，
</p>
<p>
他在虐掉一名卫兵（或者发现这个城市没有卫兵）之后，就会继续朝着首都方向
</p>
<p>
赶路。而当他赶到了首都并虐了一名首都的卫兵（或者发现首都也没有卫兵）之
</p>
<p>
后，就要被强制回老家结婚了。
</p>
<p>
显然，一定存在某个时刻，使得A 国的所有城市恰好都被占领了。你的任务
</p>
<p>
就是求出这样的时刻。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行含有一个整数n ，含义如文中所述。
</p>
<p>
接下来一行含有n 个非负整数，第i 个整数为di，含义如文中所述。保证边
</p>
<p>
界城市满足 di=0，同时，保证所有非边界城市满足di！=0 。
</p>
<p>
接下来n-1行，每行含有三个整数，描述一条道路。第i 行的三个整数为
</p>
<p>
xi，yi，zi代表编号为xi 和yi 的城市之间有一条长度为li 的道路。保证道路网络构
</p>
<p>
成一棵树。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个整数，表示A 国的所有城市恰好都被占领的时刻。
</p>
<h3>
【样例输入】
</h3>
<p>
5
</p>
<p>
5 10 0 0 0
</p>
<p>
1 2 3
</p>
<p>
1 3 10
</p>
<p>
2 4 1
</p>
<p>
2 5 2
</p>
<h3>
【样例输出】
</h3>
<p>
7
</p>
<h3>
【提示】
</h3>
<p>
n&lt;=100000 所有数据小于 2^63-1
</p>
<h3>
【来源】
</h3>
<p>
上传by zys
</p>