# 题目描述


<p>
<br/>
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">问题描述：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一位信使来到一个村落送信，不幸的事由于下雨他的信件信封上的地址都模糊不清，只剩下连续的一小部分可以辨认。村落中共有<span>m</span><span>户居民，每户村民的地址可以用一个只含有小写字母的字符串表示，第</span><span>i</span><span>户村民的地址为</span><span>Ai;</span><span>信使需要投送</span><span>n</span><span>封信件，第</span><span>j</span><span>封信件信封上可以辨认的部分地址记作</span><span>Bj</span><span>，若</span><span>Bj</span><span>为</span><span>Ai</span><span>的子串，则第</span><span>i</span><span>户家庭可能为第</span><span>j</span><span>封信件的收件人。最坏情况下，信使可能需要走遍一封信件的所有可能收件人才能将信件投送出去。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一些信件还附带有包裹，因此每封信件都有一个重量值<span>Wi</span><span>，信使从一户村民</span><span>X</span><span>移动到另一户村民</span><span>Y</span><span>的代价为到达</span><span>Y</span><span>时身上所携带的信件重量只和。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">信使不想走太长的路，因此他希望每户人家只经过一次，即所走的路径为一条链，在这个前提下他请你帮他设计一条路线，使得在最坏情况下投送完所有信件所花费的代价最小。<br/>
<br/>
</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入格式：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入数据共<span>n+m+1</span><span>行：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第<span>1</span><span>行为两个整数</span><span>m</span><span>、</span><span>n</span><span>，表示村落中共有</span><span>m</span><span>户村民，信使需要投送</span><span>n</span><span>封信件。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第<span>2</span><span>行到第</span><span>m+1</span><span>行每行为一个字符串，表示第每户村民的地址。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第<span>m+2</span><span>行到第</span><span>n+m+1</span><span>行每行有一个整数和一个字符串，表示每封信件的重量以及可辨认出的地址。<br/>
<br/>
</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出格式：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出数据仅有<span>1</span><span>行，为在最坏情况下的最小代价。<br/>
<br/>
</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入样例<span>(</span></span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">postman</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">a.in)<span>：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">ab</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 ab<br/>
<br/>
</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出样例：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5<br/>
<br/>
样例解释：<br/>
信使的路线为ab-&gt;b-&gt;a，最坏情况下在ab投送出第三封信，在b投送出第二封信，在a投送出第一封信。ab-&gt;b的代价为1+3=4，b-&gt;a的代价为1，总代价和为5。<br/>
<br/>
</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">数据规模：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10%<span>的数据满足</span><span>1</span><span>≤</span><span>m,n</span><span>≤</span><span>15<br/>
</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">30%<span>的数据满足</span><span>1</span><span>≤</span><span>m,n</span><span>≤</span><span>100</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">100%<span>的数据满足</span><span>1</span><span>≤</span><span>m,n</span><span>≤</span><span>5000, 0</span><span>≤</span><span>Wi</span><span>≤</span><span>100, </span><span>每个信件的字符串的长度</span><span>Ln</span><span>≤</span><span>300，每户村民的地址字符串长度Lm<span style="font-family:宋体;font-size:14px;line-height:21px;">≤2000。</span></span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">数据保证每封信件都至少有一个可能的收信人，且每户村民都至少成为一封信件的可能收信人。</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"></span> 
</p>
<p>
<br/>
</p>
