# 题目描述


<div>
USACO/wissqu(译 by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">威斯康星州的春天来了，是该把小奶牛们赶到小牧场上并把大奶牛们赶到北纬 40 度的大牧场上的时候了。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">农夫约翰的牧场上有五种奶牛（括号内的是缩写）：格恩西奶牛（A），泽西奶牛（B），赫里福奶牛（C），黑安格斯奶牛（D），朗赫恩奶牛（E）。这些奶牛群放养在一片 16 英亩的牧场上，每英亩上都有一小群奶牛，像下面这样排列成 4 x 4 的格子（用行和列标号）：</span>
</p>
<div align="center">
<pre>  1 2 3 4
 +-------
1|A B A C
2|D C D E
3|B E B C
4|C A D E

  </pre>
</div>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">最初，牧场上的奶牛群总共有 3 群 A，3 群 B，4 群 C，3 群 D，3 群 E。今年的 D 种小奶牛比去年多一群 ，C 种少一群，共有 3 群 A，3 群 B，3 群 C，4 群 D，3 群 E。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">农夫约翰对于他牧场上的奶牛群的布局非常小心。这是因为如果同一种类型的奶牛群靠得太近，她们就乱来：她们聚集在栅栏边上抽烟，喝牛奶。如果她们在相同的格子上或者在临近的 8 个格子上，就是靠得太近了。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">农夫约翰得用他的棕色旧福特皮卡把他的大奶牛群运出牧场，并把他的小奶牛群运进牧场，皮卡一次只能运一群奶牛。他装上一群小奶牛，开车到小牧场的一个方格中，卸下这群小奶牛，再装上这个格子上的那群大奶牛，开到北纬 40 度的大牧场卸下来。他重复这样的操作 16 次，然后开车去杰克商店办理低脂酸奶的交易和家居装修。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">帮助农夫约翰。他必须选择正确的顺序来替换他的奶牛群，使得他从不把一群小奶牛放入当前被同样类型奶牛占有的方格或者当前被同样类型奶牛占据的方格的临近方格。当然，一旦大奶牛走了，小奶牛来了，他必须小心以后的情况，要根据新的排列把奶牛群分开。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">非常重要的提示：农夫约翰从过去的经验知道，他必须先移动 D 种奶牛群。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">找出农夫约翰将他的小奶牛搬迁到她们的新牧场上的办法。输出 16 个连续的 奶牛群类型/行/列 的信息，使得这样的安排能够符合安全经验。 </span> 
</p>
<span style="font-family:&#39;Times New Roman&#39;;"> 
<p>
<span style="font-family:&#39;Times New Roman&#39;;">计算 4 x 4 牧场的最终排列总数（这应该是原题作者的笔误，输出样例中并没有说明要输出最终排列总数，此题只有一个测试数据，也没有体现这个问题——译者注），和产生那些排列的方式的总数。</span> 
</p>
<p>
 
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: wissqu </span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT (file wissqu.in)</span> 
</h3>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">四行，每行四个用空格分开的字母，表示奶牛群（又是原题作者的笔误了，字母之间没有空格——译者注）。 </span> 
</p>
<p>
<br/>
</p>
<p>
 
</p>
<h3>
OUTPUT FORMAT(file wissqu.out)
</h3>
<p>
16 行，每行分别由 奶牛群类型/行/列 组成。如果有多解（一定有），那么你应该输出奶牛群类型按照字典序排列在最前面的那个解。如果不只一个解满足条件，那么你应该输出行信息按照字典需排列在最前面的那个解。如果仍然不只一个解满足条件，那么你应该输出列信息按照字典序排列在最前面的那个解。
</p>
<p>
最后多输出一行，包含能够由这个排列方式产生的排列的总数。
</p>
<p>
<br/>
</p>
<p>
 
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file wissqu.in) </span> 
</h3>
<span style="font-family:宋体;">ABAC<br/>
DCDE<br/>
BEBC<br/>
CADE </span> 
<p>
<br/>
</p>
<p>
 
</p>
<h3>
SAMPLE OUTPUT (file wissqu.out)
</h3>
<span style="font-family:宋体;">D 4 1<br/>
C 4 2<br/>
A 3 1<br/>
A 3 3<br/>
B 2 4<br/>
B 3 2<br/>
B 4 4<br/>
E 2 1<br/>
E 2 3<br/>
D 1 4<br/>
D 2 2<br/>
C 1 1<br/>
C 1 3<br/>
A 1 2<br/>
E 4 3<br/>
D 3 4<br/>
14925</span> 
<p>
<br/>
</p>
<p>
 
</p>
</span>
