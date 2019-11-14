# 题目描述


<p>
<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">题目描述：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:24.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">像每个人一样，奶牛们喜欢在排队等待领取食物和自己的朋友站在一起。<span>FJ</span><span>拥有</span><span>N</span><span>头奶牛，编号为</span><span>1</span><span>至</span><span>N</span><span>。它们站成一行，等待</span><span>FJ</span><span>派送奶牛营养餐。这些奶牛按照编号大小排列，并且由于它们都很想早点吃饭，于是就很可能出现多头奶牛挤在同一位置的情况</span><span>(</span><span>也就是说，如果我们认为奶牛位于数轴上，那么多头奶牛的位置坐标可能相同</span><span>)</span><span>。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:24.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">某些奶牛之间互相喜欢，它们希望互相之间的距离至多为一个定值。某些奶牛之间互相厌恶，它们希望互相之间的距离至少为一个定值。现在给定<span>ML</span><span>个互相喜爱的奶牛对以及它们之间距离的最大值，</span><span>MD</span><span>个互相厌恶的奶牛对以及它们之间距离的最小值。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">    你的任务是计算在满足以上条件的前提下，编号为<span>1</span><span>和编号为</span><span>N</span><span>的奶牛之间距离的最大可能值。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">输入描述：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:24.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">输入文件第一行三个整数<span>N,ML</span><span>以及</span><span>MD</span><span>。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:24.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">此后<span>ML</span><span>行，每行包含三个用空格分开的整数</span></span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">A,B</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">和</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">D</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，其中<span>A,B</span><span>满足</span></span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1&lt;=A<b<= n<="" span=""><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。表示编号为</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">A</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">和</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">B</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">的奶牛之间的距离至多为</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">D</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> </b<=></span> 
</p>
<p style="text-indent:24.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">此后<span>MD</span><span>行，每行包含三个用空格分开的整数</span></span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">A,B</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">和</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">D</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，其中<span>A,B</span><span>满足</span></span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1&lt;=A<b<= n<="" span=""><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。表示编号为</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">A</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">和</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">B</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">的奶牛之间的距离至少为</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">D</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> </b<=></span> 
</p>
<p>
<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">输出描述：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:24.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">输出文件仅包含一个整数。如果不存在任何合法的排队方式，就输出<span>-1</span><span>。如果编号</span><span>1</span><span>和编号</span><span>N</span><span>的奶牛间距离可以任意，就输出</span><span>-2</span></span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。否则输出它们之间的最大可能距离。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">输入样例：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">4 2 1</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1 3 10</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">2 4 20</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">2 3 3</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">输出样例：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">27</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">数据约定：</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">N&lt;=1000<span>；</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">ML,MN&lt;=10000<span>；</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">D&lt;=1000000<span>。</span></span> 
</p>
<p>
<br/>
</p>
<p>
中小学电脑报<span> NOI导刊 NOIP2012河南省实验中学培训 Day4 Exercise Problem 10</span><br/>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><span></span></span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
