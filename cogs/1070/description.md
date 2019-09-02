

# 问题描述



# 输入


<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">第一行包含一个正整数</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">N</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">（</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1&lt;=N&lt;=300000</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">）</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">,</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">表示图的顶点数。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;background:#FFFFFF;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">第二行包含由空格隔开</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">N</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">个正整数，第</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">i</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">个数表示从</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">i</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">顶点可以通过出边到达的定点编号，</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">0</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">表示该点没有出边。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;background:#FFFFFF;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">接下来的一行包含</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">个整数</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">Q</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">（</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1&lt;=Q&lt;=300000</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">）</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">,</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">表示询问的次数。</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">再接下来Q行，每行表示一次查询，格式如题目描述。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>

# 输出


<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">对于第</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">类询问，输出玻璃球停止时所在顶点编号</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">,</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">每行</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">个，按照查询的顺序输出。如果玻璃球无法停止，输出</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">”</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">CIKLUS</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;background:#FFFFFF;">”</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">即可<span>.</span></span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;background:#FFFFFF;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>

# 输入输出样例<span>1</span><span>


<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
<tbody>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">

# 输入输出样例<span>2</span><span>


<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
<tbody>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">

# 数据范围


<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   40% <span>数据保证  </span><span>N&lt;=100,  Q&lt;=1000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:16.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span> 
</p>
