# 题目描述


<p style="text-align:center;" align="center">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Molecular</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">给你一些原子的质量，请你计算他们所构成的分子式质量。</span><span style="font-size:12.0pt;"></span> 
</p>
<p>
<span style="font-size:12.0pt;"></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输入格式</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">若干行，每行一个原子，后面接它的质量，中间由多个空格隔开。</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">原子质量描述以“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">END_OF_FIRST_PART</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">”结束。</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">接下来，每行一个分子式，以“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">0</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">”表示数据结束</span><span style="font-size:12.0pt;"></span> 
</p>
<p>
<span style="font-size:12.0pt;"></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输出格式</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">若干行，每行是对应分子式的质量，如果某分子式中不知道某原子的质量，则输出“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">UNKNOWN</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">”</span><span style="font-size:12.0pt;"></span> 
</p>
<p>
<span style="font-size:12.0pt;"></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">样例</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输入</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">H 1</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">He 4</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">C 12</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">O 16</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">F 19</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Ne 20</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Cu 64</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Cc 333</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">END_OF_FIRST_PART</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">H2C</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">(MgF)2As</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Cu(OH)2</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">H((CO)2F)99</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">0</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输出</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">14</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">UNKNOWN</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">98</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">7426</span> 
</p>
<p>
<span style="font-size:12.0pt;"></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">数据说明</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">数据保证分子式是一定符合化学规则的。</span><span style="font-size:12.0pt;"></span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">每一个分子式长度</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">&lt;=80</span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">每一个分子包含的原子总数</span><span style="font-size:12.0pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">&lt;=10</span><sup><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">5</span></sup></span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">每一个原子对应的质量</span><span style="font-size:12.0pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">&lt;=10</span><sup><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">3</span></sup></span> 
</p>
<p style="text-indent:24.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">每个数据不超过</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">10</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">个分子式</span><span style="font-size:12.0pt;"></span> 
</p>
