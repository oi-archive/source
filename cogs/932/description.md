# 题目描述


<p>
<span style="font-family:宋体;"><b><span style="font-size:18px;">【问题描述</span></b><span style="font-size:18px;">】 </span></span> 
</p>
<p>
<span></span><span style="font-size:18px;">我们经常用一个较短的字符串来代替一个很长的名称，比如，ACM就是“Association for Computing Machinery”的缩写。现在我们要采用一个关于首字母缩写词的规则来取得一个名称的缩写，一个首字母缩写词是这样产生的：把名称中每一个单词的首字母的大写形式连接在一起即可。但是也有例外，那就是有些单词必须忽略掉，这些单词（不区分大小写）包含下面两类：</span><br/>
<span style="font-size:18px;"> （1）几个普通的单词：&#34;and&#34;,&#34;for&#34;,和&#34;the&#34;；</span><br/>
<span style="font-size:18px;"> （2）长度小于3的单词，如&#34;a&#34;，&#34;of&#34;,&#34;to&#34;等。</span><br/>
<span style="font-size:18px;"> 你的任务是对于给定的字符串，使用以上规则取得其缩写形式。</span> 
</p>
<p>
<strong><span style="font-size:18px;">【输入格式】</span></strong> 
</p>
<p>
<span style="font-size:18px;"><span style="font-size:18px;"> 输入文件的第一行是一个正整数T（T&lt;=100)，表示接下来测试数据的数目。每一个测试数据包含一个长度不超过100的字符串S，表示一个等待被取得缩写的名称，S中仅包含字母，两个单词之间只有一个空格，字符串首尾均无多余空格。</span></span> 
</p>
<p>
<span><span></span></span><span></span><strong><span style="font-size:18px;">【输出格式】</span></strong> 
</p>
<p>
<span style="font-size:18px;">  对于每一个测试数据，输出S的缩写。</span> 
</p>
<p>
<strong><span style="font-size:18px;">【样例】</span></strong> 
</p>
<p>
<span style="font-size:18px;">abbreviation.in</span><br/>
<span style="font-size:18px;"> 5</span><br/>
<span style="font-size:18px;"> Association for Computer Machinery</span><br/>
<span style="font-size:18px;"> Institute of Electrical and Electronics Engineers</span><br/>
<span style="font-size:18px;"> SUN YAT SEN UNIVERSITY</span><br/>
<span style="font-size:18px;"> The Lord of the Rings</span><br/>
<span style="font-size:18px;"> netease</span> 
</p>
<p>
<br/>
</p>
<span> 
<p>
<span style="font-size:18px;">abbreviation.out</span><br/>
<span style="font-size:18px;"> ACM</span><br/>
<span style="font-size:18px;"> IEEE</span><br/>
<span style="font-size:18px;"> SYSU</span><br/>
<span style="font-size:18px;"> LR</span><br/>
<span style="font-size:18px;"> N</span><span></span> 
</p>
</span>
