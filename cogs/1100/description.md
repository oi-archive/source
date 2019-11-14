# 题目描述


<p>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;">2012年清北学堂国庆节培训中，贾志豪同学在讲动态规划时，讲到了这个题目，所以就添加到题库里~</span> 
</p>
<p>
<span><span style="line-height:16.79px;">以下并非官方翻译，请参照<a href="http://tjsct.wikidot.com/usaco-open08-gold" target="_blank">英文原版试题</a>理解题意。</span></span> 
</p>
<h3>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;"></span> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
FJ和他的一群喜欢跳舞的异国奶牛在为他们新的moosical练习，&#34;The Street Cow Named Desire&#34;。在排练的过程中，他的奶牛重叠成了N(1 &lt;= N &lt;= 1,000)个以30头为单位的栈，每头牛都在另一头牛的背上(他们精神都有些问题)。牧场分布着这些栈和M(1 &lt;= M &lt;= 1,000)个干草堆，例如：
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
                8 ......... <br/>
                7 ....CH.H.         C = stack of 30 cows <br/>
                6 ......... <br/>
                5 .........         H = haystack <br/>
                4 ..C.HH... <br/>
                3 ......... <br/>
                2 .....C.HH <br/>
                1 ......... <br/>
                  123456789
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
(如果你的浏览器字体不是等宽字体，那么请参照下图理解上“图”)
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
<img alt="" src="/upload/image/20121004/20121004185532_93627.png"/> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
<span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">作为指挥家，FJ会4种不同声调的口哨。分别使这每叠牛向北、向南、向西、向东移动一个单位距离。<span></span></span> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
<span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;"><span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">如果这一叠牛遇到了一个干草堆，最顶上的那头牛就会跳到干草堆上(即使再高)，其余的不变。</span></span> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
<span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;"><span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">也就是说，如果这叠牛遇到了30次干草堆，最底下的那头牛就也站到了干草堆上。</span></span> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
<span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;"><span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">这些坚固的干草堆支持无限多头奶牛站上去。</span><br/>
</span> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
<span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;"><span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">FJ随时观察着他的挤奶设施。突然他发现，一个巨大的牛奶罐爆炸了，牛奶正不停向这些正在跳舞的奶牛涌来。只要在干草堆上的奶牛就是安全的，FJ现在必须拯救奶牛们的生命<span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">(⊙﹏⊙b汗)</span><span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;"></span>。<span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">FJ可是吹K(1 &lt;= K &lt;= 30)次口哨，每叠奶牛和干草堆的坐标X_i, Y_i (1 &lt;= X_i &lt;= 1,000; 1 &lt;= Y_i &lt;= 1,000) 是已知的。请计算FJ最多能救多少头奶牛，且输出每次移动的方案。奶牛的坐标和干草堆的坐标不会相同。</span></span></span> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
<span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;"><span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;"><span style="color:#333333;line-height:17.6px;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">奶牛可以被移动到任何位置，包括牧场之外。</span></span></span> 
</p>
<p>
<br/>
</p>
<p>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">可适当参照清北学堂讲师的转述：</span> 
</p>
<p>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;"><img alt="" src="/upload/image/20121004/20121004185705_39378.png"/><br/>
</span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;"> </span> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
* Line 1: Three space-separated integers: N, M, and K
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
* Lines 2..N+1: Line i+1 describes the X,Y location of a stack of 30 <br/>
        cows using two space-separated integers: X_i and Y_i
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
* Lines N+2..N+M+1: Line i+N+1 describes the X,Y location of a <br/>
        haystack using two space-separated integers: X_i and Y_i
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;"> </span> 
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
* Line 1: A single integer that is the most number of cows that can be <br/>
        saved.
</p>
<p style="text-align:justify;color:#333333;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;background-color:#FFFFFF;">
* Line 2: K characters, the lexicographically least sequence of <br/>
        commands FJ should issue to maximize the number of cows saved.
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>3 6 3
3 4
6 2
5 7
8 2
9 2
6 4
5 4
6 7
8 7</pre>
<h3>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>6
EEE</pre>
<h3>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;">【提示】</span> 
</h3>
<p>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;"> </span> 
</p>
<pre>OUTPUT DETAILS:

Use the &#39;east&#39; whistle three times, at which point the milk floods
the area.  Each haystack ends up saving 1 cow.</pre>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;">【来源】</span> 
</h3>
<p>
<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:14px;"></span> 
</p>
<h4 style="color:#444444;font-family:&#34;Hiragino Sans GB W3&#34;, sans-serif;font-size:14.39px;font-weight:normal;background-color:#FFFFFF;">
[Usaco Open08 Gold]
</h4>
<p>
<br/>
</p>
