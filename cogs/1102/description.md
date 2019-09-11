# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"><span style="font-size:14.399999618530273px;line-height:16.799999237060547px;font-family:&#39;Microsoft YaHei&#39;;">保卫钓鱼岛！为了迎战XX国，OO国在钓鱼岛上建起了N个连通的碉堡(就是碉堡，没别的意思)，N-1条沟壕（构成了一棵树）。</span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"><span style="font-size:14.399999618530273px;line-height:16.799999237060547px;font-family:&#39;Microsoft YaHei&#39;;"><span></span>每个碉堡的高度都不相同（父结点的高度必然大于子结点），相邻碉堡间由沟壕相连。由于钓鱼岛上没有什么高端工具，所以OO国的军用物资只能从高处运往低处，而且每完成一次碉堡间的物资运输，都要花费一定的时间。OO国拟举行M次物资运输演习，每次从碉堡u运到碉堡v，当然其中有不少演习是没有办法完成的（因为要上坡）。OO国司令想知道OO国军队能完成多少个物资运输演习，并且想知道完成这些演习的总用时。（忽略一切其他的耗时） <br/>
</span></span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行两个整数n，m。 <br/>
接下来n-1行每行3个整数a、b、t。 <br/>
表示OO国军队的军用物资可以花t秒从第a个碉堡运输到第b个碉堡。 <br/>
接下来m行每行2个整数u、v，意义如描述所示。 <br/>
</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行输出一个正整数，表示能完成的演习数。 <br/>
第二行输出一个正整数，表示总用时。<br/>
</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>6 2
1 2 1
2 4 1
2 5 1
5 6 1
1 3 1
2 6
4 5
</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>1
2
</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【提示】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">各个测试点1s </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一个碉堡的高度是最高的；若u=v则不能完成物资运输演习。<br/>
对于50％的数据 n≤1000 m≤1000； <br/>
对于100％的数据 n≤10000 m≤100000； <br/>
答案小于2^64。</span> 
</p>
