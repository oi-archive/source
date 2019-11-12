# 题目描述


<p>
<br/>
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:12.0pt;font-family:仿宋;">【题目描述】</span></b><b><span style="font-size:12.0pt;font-family:&#34;"></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">不要紧张。题目的名字只是一个</span><span style="font-size:12.0pt;font-family:&#34;">MD5</span><span style="font-size:12.0pt;font-family:仿宋;">。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">小</span><span style="font-size:12.0pt;font-family:&#34;">A</span><span style="font-size:12.0pt;font-family:仿宋;">有一堆小圆点。某天，他无聊了，于是他想把这些点连成一棵无根树。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">小</span><span style="font-size:12.0pt;font-family:&#34;">A</span><span style="font-size:12.0pt;font-family:仿宋;">觉得他不能放过这个防</span><span style="font-size:12.0pt;font-family:&#34;">AK</span><span style="font-size:12.0pt;font-family:仿宋;">的好机会，于是他想借此考考你。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">一开始，小</span><span style="font-size:12.0pt;font-family:&#34;">A</span><span style="font-size:12.0pt;font-family:仿宋;">有</span><span style="font-size:12.0pt;font-family:&#34;">n</span><span style="font-size:12.0pt;font-family:仿宋;">个点，这</span><span style="font-size:12.0pt;font-family:&#34;">n</span><span style="font-size:12.0pt;font-family:仿宋;">个点分别编号为</span><span style="font-size:12.0pt;font-family:&#34;">1~n</span><span style="font-size:12.0pt;font-family:仿宋;">。每个点都有颜色，任何时刻，点的颜色都只能是黑白两种颜色之一。初始时，所有点都是白色的。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">小</span><span style="font-size:12.0pt;font-family:&#34;">A</span><span style="font-size:12.0pt;font-family:仿宋;">一共会进行</span><span style="font-size:12.0pt;font-family:&#34;">m</span><span style="font-size:12.0pt;font-family:仿宋;">次操作，每次操作只可能是以下的三种之一：</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">A u v w</span><span style="font-size:12.0pt;font-family:仿宋;">：添加一条连接</span><span style="font-size:12.0pt;font-family:&#34;">(u,v)</span><span style="font-size:12.0pt;font-family:仿宋;">的无向边，长度为</span><span style="font-size:12.0pt;font-family:&#34;">w</span><span style="font-size:12.0pt;font-family:仿宋;">。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">C u</span><span style="font-size:12.0pt;font-family:仿宋;">：反转点</span><span style="font-size:12.0pt;font-family:&#34;">u</span><span style="font-size:12.0pt;font-family:仿宋;">的颜色，即如果点</span><span style="font-size:12.0pt;font-family:&#34;">u</span><span style="font-size:12.0pt;font-family:仿宋;">原来是白色则反转后会变成黑色，反之亦然。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">Q u</span><span style="font-size:12.0pt;font-family:仿宋;">：询问所有与点</span><span style="font-size:12.0pt;font-family:&#34;">u</span><span style="font-size:12.0pt;font-family:仿宋;">连通的黑点到点</span><span style="font-size:12.0pt;font-family:&#34;">u</span><span style="font-size:12.0pt;font-family:仿宋;">的距离之和。定义连通的两点间的距离为两点间简单路径上的边长度之和。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">因为小</span><span style="font-size:12.0pt;font-family:&#34;">A</span><span style="font-size:12.0pt;font-family:仿宋;">觉得这个问题太简单了，所以他决定强制在线。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:12.0pt;font-family:仿宋;">【输入格式】</span></b><b><span style="font-size:12.0pt;font-family:&#34;"></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">第一行一个整数</span><span style="font-size:12.0pt;font-family:&#34;">T</span><span style="font-size:12.0pt;font-family:仿宋;">，表示测试点编号。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">第二行两个整数</span><span style="font-size:12.0pt;font-family:&#34;">n,m</span><span style="font-size:12.0pt;font-family:仿宋;">，分别表示点的个数和操作数。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">以下</span><span style="font-size:12.0pt;font-family:&#34;">m</span><span style="font-size:12.0pt;font-family:仿宋;">行，每行描述一个操作，格式如上所述。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">为了防止你采用各种离线算法水掉本题，本题强制在线，每次输入的整数均需异或</span><span style="font-size:12.0pt;font-family:&#34;">(</span><span style="font-size:12.0pt;font-family:仿宋;">上一次询问的答案</span><span style="font-size:12.0pt;font-family:&#34;">mod n)</span><span style="font-size:12.0pt;font-family:仿宋;">。如果还没有进行询问，那么上一次询问的答案是</span><span style="font-size:12.0pt;font-family:&#34;">0</span><span style="font-size:12.0pt;font-family:仿宋;">。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">注意，</span><span style="font-size:12.0pt;font-family:&#34;">mod n</span><span style="font-size:12.0pt;font-family:仿宋;">是在</span><span style="font-size:12.0pt;font-family:&#34;">n</span><span style="font-size:12.0pt;font-family:仿宋;">的剩余系下，比如</span><span style="font-size:12.0pt;font-family:&#34;">-1 mod 5 = 4.</span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:12.0pt;font-family:仿宋;">【样例输入】</span></b><b><span style="font-size:12.0pt;font-family:&#34;"></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">3 7</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">A 1 2 3</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">C 1</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">Q 2</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">Q 3</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">A 2 3 1</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">C 2</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">Q 3</span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:12.0pt;font-family:仿宋;">【样例输出】</span></b><b><span style="font-size:12.0pt;font-family:&#34;"></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">3</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">0</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">5</span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:12.0pt;font-family:仿宋;">【样例解释】</span></b><b><span style="font-size:12.0pt;font-family:&#34;"></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">样例输入解密后为</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">3 7</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">A 1 2 3</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">C 1</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">Q 2</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">Q 3</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">A 2 3 1</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">C 2</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;">Q 3</span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:12.0pt;font-family:仿宋;">【数据范围与约定】</span></b><b><span style="font-size:12.0pt;font-family:&#34;"></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">本题共有</span><span style="font-size:12.0pt;font-family:&#34;">20</span><span style="font-size:12.0pt;font-family:仿宋;">个测试点，每个测试点的数据范围和特殊性质如下：</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<div align="center">
<table class="MsoTable15Grid2Accent6" border="1" cellspacing="0" cellpadding="0" style="border-collapse:collapse;border:none;">
<tbody>
<tr>
<td width="95" style="border:1.5pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">测试点编号</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
<td width="94" style="border:1.5pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">n</span> 
</p>
</td>
<td width="95" style="border:1.5pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">m</span> 
</p>
</td>
<td width="264" style="border:1.5pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">特殊性质</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">1</span> 
</p>
</td>
<td width="94" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">=10</span> 
</p>
</td>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">=30</span> 
</p>
</td>
<td width="264" rowspan="6" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">无</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">2</span> 
</p>
</td>
<td width="94" rowspan="3" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=100</span> 
</p>
</td>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=200</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">3</span> 
</p>
</td>
<td width="95" rowspan="2" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=500</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">4</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">5</span> 
</p>
</td>
<td width="94" rowspan="2" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=500</span> 
</p>
</td>
<td width="95" rowspan="2" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=1000</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">6</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">7</span> 
</p>
</td>
<td width="94" rowspan="2" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=2000</span> 
</p>
</td>
<td width="95" rowspan="2" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=5000</span> 
</p>
</td>
<td width="264" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">所有</span><span style="font-size:12.0pt;font-family:&#34;">A</span><span style="font-size:12.0pt;font-family:仿宋;">操作在其他操作之前</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">8</span> 
</p>
</td>
<td width="264" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">无</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">9</span> 
</p>
</td>
<td width="94" rowspan="4" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=50000</span> 
</p>
</td>
<td width="95" rowspan="4" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=200000</span> 
</p>
</td>
<td width="264" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">具有以下两个测试点的特殊性质</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">10</span> 
</p>
</td>
<td width="264" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">所有</span><span style="font-size:12.0pt;font-family:&#34;">A</span><span style="font-size:12.0pt;font-family:仿宋;">操作在其他操作之前</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">11</span> 
</p>
</td>
<td width="264" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">树的形态随机</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">12</span> 
</p>
</td>
<td width="264" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">每个点的度不超过</span><span style="font-size:12.0pt;font-family:&#34;">2</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">13</span> 
</p>
</td>
<td width="94" rowspan="8" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=100000</span> 
</p>
</td>
<td width="95" rowspan="8" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">&lt;=300000</span> 
</p>
</td>
<td width="264" rowspan="8" style="border:1pt solid #A8D08D;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">无</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">14</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">15</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">16</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">17</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">18</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">19</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">20</span> 
</p>
</td>
</tr>
<tr>
<td width="95" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:&#34;">1~20</span> 
</p>
</td>
<td width="453" colspan="3" style="border:solid #A8D08D 1.0pt;background:#E2EFD9;">
<p class="MsoNormal" align="center" style="text-align:center;">
<span style="font-size:12.0pt;font-family:仿宋;">保证所有边的长度绝对值</span><span style="font-size:12.0pt;font-family:&#34;">&lt;=10000</span> 
</p>
</td>
</tr>
</tbody>
</table>
</div>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:仿宋;">你可以假定给出的所有操作均合法，即进行</span><span style="font-size:12.0pt;font-family:&#34;">A</span><span style="font-size:12.0pt;font-family:仿宋;">操作后一定不会产生环，给出的点的编号都在</span><span style="font-size:12.0pt;font-family:&#34;">1~n</span><span style="font-size:12.0pt;font-family:仿宋;">之内。但请注意，数据不保证最后得到的一定是一棵树</span><span style="font-size:12.0pt;font-family:&#34;">(</span><span style="font-size:12.0pt;font-family:仿宋;">也即所有点可能不连通</span><span style="font-size:12.0pt;font-family:&#34;">)</span><span style="font-size:12.0pt;font-family:仿宋;">。</span><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:21pt;">
<span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p>
<br/>
</p>
