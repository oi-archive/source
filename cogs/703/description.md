# 题目描述


<p>
<b><span style="font-family:宋体;font-size:12pt;">问题描述：</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;">二进制病毒审查委员会最近发现了如下的规律：某些确定的二进制串是病毒的代码。如果某段代码中不存在任何一段病毒代码，那么我们就称这段代码是安全的。现在委员会已经找出了所有的病毒代码段，试问，是否存在一个无限长的安全的二进制代码。</span> 
</p>
<p>
<span style="font-family:黑体;font-size:12pt;">示例：</span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;">例如如果</span><span>{011, 11, 00000}</span><span style="font-family:宋体;">为病毒代码段，那么一个可能的无限长安全代码就是</span><span>010101…</span><span style="font-family:宋体;">。如果</span><span>{01, 11, 000000}</span><span style="font-family:宋体;">为病毒代码段，那么就不存在一个无限长的安全代码。</span> 
</p>
<p>
<span style="font-family:黑体;font-size:12pt;">任务：</span><span style="font-size:12pt;"></span> 
</p>
<p>
<span style="font-family:宋体;">请写一个程序：<span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:45pt;">
<span style="font-family:Wingdings;"><span>l<span> </span></span></span><span style="font-family:宋体;">在文本文件wir</span><span>.in</span><span style="font-family:宋体;">中读入病毒代码；</span> 
</p>
<p style="text-indent:-21pt;margin-left:45pt;">
<span style="font-family:Wingdings;"><span>l<span> </span></span></span><span style="font-family:宋体;">判断是否存在一个无限长的安全代码；</span> 
</p>
<p style="text-indent:-21pt;margin-left:45pt;">
<span style="font-family:Wingdings;"><span>l<span> </span></span></span><span style="font-family:宋体;">将结果输出到文件<span>wir</span></span><span>.out</span><span style="font-family:宋体;">中</span><span style="font-family:宋体;">。<span></span></span> 
</p>
<p>
<span style="font-family:黑体;font-size:12pt;">输入格式（</span><span>wir.in</span><span style="font-family:宋体;">）</span><span style="font-family:黑体;font-size:12pt;">：</span><span style="font-size:12pt;"></span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;">在文本文件</span><span>WIR.IN</span><span style="font-family:宋体;">的第一行包括一个整数</span><span>n</span><span style="font-family:宋体;">，表示病毒代码段的数目。以下的</span><span>n</span><span style="font-family:宋体;">行每一行都包括一个非空的</span><span>01</span><span style="font-family:宋体;">字符串——就是一个病毒代码段。所有病毒代码段的总长度不超过</span><span>30000</span><span style="font-family:宋体;">。</span> 
</p>
<p>
<span style="font-family:黑体;font-size:12pt;">输出格式（</span><span><span>wir</span>.out</span><span style="font-family:宋体;">）</span><span style="font-family:黑体;font-size:12pt;">：</span><span style="font-size:12pt;"></span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;">在文本文件<span><span>wir</span>.out</span></span><span style="font-family:宋体;">的第一行输出一个单词：</span> 
</p>
<p style="text-indent:-21pt;margin-left:45pt;">
<span style="font-family:Wingdings;"><span>l<span> </span></span></span><span>TAK</span><span style="font-family:宋体;">——假如存在这样的代码；</span> 
</p>
<p style="text-indent:-21pt;margin-left:45pt;">
<span style="font-family:Wingdings;"><span>l<span> </span></span></span><span>NIE</span><span style="font-family:宋体;">——如果不存在。</span> 
</p>
<p>
<span style="font-family:黑体;font-size:12pt;">样例</span><span style="font-size:12pt;">:</span> 
</p>
<p>
<span style="font-family:宋体;">输入（<span><span>wir</span>.in</span></span><span style="font-family:宋体;">）：</span> 
</p>
<pre><span style="font-family:&#39;Courier New&#39;;">3</span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">01 </span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">11 </span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">00000</span></pre>
<p>
<span style="font-family:宋体;">输出（</span><span><span><span>wir</span>.out</span></span><span style="font-family:宋体;">）：</span> 
</p>
<pre><span style="font-family:&#39;Courier New&#39;;">NIE</span></pre>
