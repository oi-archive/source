# 题目描述


<p align="center" style="text-align:center;">
<b><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;background-color:#FF9900;color:#003399;">福州NOIP2010培训Day2</span></b> 
</p>
<p align="center" style="text-align:center;">
<b><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">01</span></b><b><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">迷宫</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">(maze01)</span></b> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【题目描述】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">有一个由</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">01</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">组成的</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n*n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">格迷宫，若你位于一格</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">上，那么你可以移动到相邻</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">格中的某一格</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">上，同样若你位于一格</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">上，那么你可以移动到相邻</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">格中的某一格</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">上。那么对于给定的迷宫，询问从某一格开始能移动到多少格。</span><span></span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入格式】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输入文件</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">maze01.in</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的第</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行为两个正整数</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">下面</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行，每行</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">个字符，字符只可能是</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">或者</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，字符之间没有空格。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">接下来</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行，每行</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">个用空格分隔的正整数</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">i,j</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，对应了迷宫中第</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行第</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">j</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">列的一个</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，询问从这一格开始能移动到多少格。</span><span></span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输出格式】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输出文件</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">maze01.out</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">包括</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行，对于每个询问输出答案。</span><span></span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例输入】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">2 2</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">01</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">10</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1 1</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">2 2</span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例输出】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4</span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例说明】</span><span></span> 
</p>
<p style="text-indent:20.25pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">所有格子互相可达。</span><span></span> 
</p>
<p style="text-indent:20.25pt;">
<span></span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【数据规模】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">20%</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的数据，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">10</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">；</span><span> </span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">40%</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的数据，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">50</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">；</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">50%</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的数据，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">5</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">；</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">60%</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的数据，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">；</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100%</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的数据，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1000</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1000000</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">。</span><span></span> 
</p>
<b><span style="font-size:10.5pt;font-family:;"><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;"></span><br/>
</span></b>
