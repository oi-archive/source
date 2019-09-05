# 题目描述


<h3>
【题目描述】
</h3>
<p>
在一个叫做Travian的世界里，生活着各个大大小小的部落。其中最为强大的是罗马、高卢和日耳曼。他们之间为了争夺资源和土地，进行了无数次的战斗。期间诞生了众多家喻户晓的英雄人物，也留下了许多可歌可泣的动人故事。
</p>
<p>
其中，在大大小小的部落之间，会有一些道路相连，这些道路是Travian世界里的重要枢纽，简单起见，你可以把这些部落与部落之间相连的道路看作一颗树，可见每条道路对于Travian世界的重要程度。有了这些道路，建筑工人就可以通过这些道路进行友好外交啦。
</p>
<p>
然而，事情并不会像想象的那样美好，由于资源的匮乏，相邻的部落（由一条道路相连的部落）之间经常会发生大大小小的冲突事件，更有甚者，会升级为部落之间的大型战争。
</p>
<p>
为了避免误伤，每当两个相邻的部落之间发生大型战争之时，这两个部落间的道路是不允许通行的，对于一些强大的部落，甚至能与多个相邻的部落同时开战，同样的，这些战争地带的道路十分危险，是不可通行的。
</p>
<p>
天下之势，分久必合，当两个部落经历了不打不相识的苦战之后，他们可以签订停战协议（暂时停战，以后依旧可能再次开战），这样，两个部落之间的道路又会重新恢复为可通行状态，建筑工人们又可以经过此地购买最新的大本营设计图纸来强大自己的部落了。
</p>
<p>
为了简单起见，我们把各大战争事件按发起的时间顺序依次编号（最先发起的战争编号就为 1，第二次战争编号就为 2，以此类推），当两个部落停战之时，则会直接告诉你这场战争的编号，然后这场战争就载入了史册，不复存在了，当然，这并不会影响到其他战争的编号。
</p>
<p>
建筑工人十分讨厌战争，因为战争，想从一个部落到另一个部落进行友好交流的建筑工人可能就此白跑一趟。所以，在他们出发之前，都会向你问问能不能到达他们想去的部落。
</p>
<img alt="" src="/upload/image/20171028/20171028223252_62702.png"/> <br/>
<h3>
【输入格式】
</h3>
<p>
第一行两个数 $n$ 和 $m$，$n$ 代表了一共有 $n$ 个部落，$m$ 代表了以上三种事件发生的总数。
</p>
<p>
接下来的 $n-1$ 行，每行两个数 $p,q$，代表了第 $p$ 个部落与第 $q$ 个部落之间有一条道路相连。
</p>
<p>
接下来的 $m$ 行，每行表示一件事，详见题目描述。
</p>
<h3>
【输出格式】
</h3>
<p>
每行一个“Yes”或者“No”，表示从第 $p$ 个部落出发的建筑工人能否到达第 $q$ 个部落。
</p>
<h3>
【样例输入】
</h3>
<pre>5 9
1 2
2 3
3 4
4 5
Q 1 4
C 2 1
C 4 3
Q 3 1
Q 1 5
U 1
U 2
C 4 3
Q 3 4
</pre>
<h3>
【样例输出】
</h3>
<pre>Yes
No
No
No
</pre>
<h3>
【提示】
</h3>
<p>
对于 30% 的数据 $1\le n,m\le 6000$。
</p>
<p>
对于另 30% 的数据，保证部落之间的地理关系是一条链，且 $i$ 与 $i+1$ 之间有一条道路。
</p>
<p>
对于另 30% 的数据，$1\le n,m\le 100000$。
</p>
<p>
对于 100% 的数据，$1\le n,m\le 300000$。
</p>
<h3>
【来源】
</h3>
<p>
NOIP 模拟赛 by WISCO信息组
</p>