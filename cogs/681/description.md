# 题目描述


<h2 style="font-weight:normal;margin-left:0px;font-size:19px;font-family:sans-serif;">
<span>描述 [USACO 2.1.4]</span> 
</h2>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">纪念“逝去”的Wecing</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<br/>
<span style="font-size:18px;"> 农民JOHN以拥有世界上最健康的奶牛为傲。他了解每种饲料中所包含的牛所需的最低的维他命量是多少。请你帮助农夫喂养他的牛，以保持它们的健康，使喂给牛的饲料的种数最少。</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">给出牛所需的最低的维他命量，输出给牛喂哪些种类的饲料，并且能使所需的饲料剂量最少。</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">维他命量用整数表示，每种饲料最多只能对牛使用一次，数据保证存在解。</span> 
</p>
<h2 style="font-weight:normal;margin-left:0px;font-size:19px;font-family:sans-serif;">
<span><br/>
格式</span> 
</h2>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<b><span style="font-size:18px;">PROGRAM NAME</span></b><span style="font-size:18px;">: holstein</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<b><span style="font-size:18px;">INPUT FORMAT</span></b><span style="font-size:18px;">:(holstein.in)</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">第1行：一个整数V(1&lt;=V&lt;=25)，表示需要的维他命的种类数。</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">第2行：V个整数(1&lt;=每个数&lt;=1000)，表示牛每天需要的每种维他命的最小量。</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">第3行：一个整数G(1&lt;=G&lt;=15)，表示可用来喂牛的饲料的种数。</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">下面G行，第n行表示编号为n饲料包含的各种维他命的量的多少。</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<b><span style="font-size:18px;">OUTPUT FORMAT</span></b><span style="font-size:18px;">:(holstein.out)</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">输出文件只有一行，包括</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">牛必需的最小的饲料种数P</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">后面有P个数，表示所选择的饲料编号（按从小到大排列）。</span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">如果有多个解，输出饲料序号最小的（即字典序最小）。</span> 
</p>
<h2 style="font-weight:normal;margin-left:0px;font-size:19px;font-family:sans-serif;">
<span><br/>
SAMPLE INPUT</span> 
</h2>
<pre>4
100 200 300 400
3
50 50 50 50
200 300 200 300
900 150 389 399
</pre>
<h2 style="font-weight:normal;margin-left:0px;font-size:19px;font-family:sans-serif;">
<span><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre>2 1 3</pre>
