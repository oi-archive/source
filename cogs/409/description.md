# 题目描述


<p>
 <b><span style="font-size:large;"><span style="font-weight:normal;font-size:12pt;">【问题描述】</span></span></b> 
</p>
<div>
<span style="font-size:12pt;">       </span><span style="font-size:12pt;">对于</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">个整数</span><span style="font-size:12pt;">0, 1, ……, <i>N</i>-1</span><span style="font-size:12pt;">，一个变换序列</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">可以将</span><i><span style="font-size:12pt;">i</span></i><span style="font-size:12pt;">变成</span><i><span style="font-size:12pt;">T<sub>i</sub></span></i><span style="font-size:12pt;">，其中<img alt="" src="/images/transform1(1).bmp" height="32" width="387"/></span><span style="font-size:12pt;"><img alt="" src="/images/transform2.bmp" height="31" width="180"/></span> 
</div>
<div>
<span style="font-size:12pt;"><span style="font-size:12pt;">定义</span><i><span style="font-size:12pt;">x</span></i><span style="font-size:12pt;">和</span><i><span style="font-size:12pt;">y</span></i><span style="font-size:12pt;">之间的距离<img alt="" src="/images/transform3.bmp" height="31" width="237"/></span></span><span style="font-size:12pt;">。给定每个</span><i><span style="font-size:12pt;">i</span></i><span style="font-size:12pt;">和</span><i><span style="font-size:12pt;">T<sub>i</sub></span></i><span style="font-size:12pt;">之间的距离</span><i><span style="font-size:12pt;">D</span></i><span style="font-size:12pt;">(<i>i</i>,<i>T<sub>i</sub></i>)</span><span style="font-size:12pt;">，</span> 
</div>
<div>
<span style="font-size:12pt;">你需要求出一个满足要求的变换序列</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">。如果有多个满足条件的序列，输出其中字典序最小的一个。</span> 
</div>
<div>
 
</div>
<div>
<b><u><span style="font-size:12pt;">说明</span></u></b><span style="font-size:12pt;">：对于两个变换序列</span><i><span style="font-size:12pt;">S</span></i><span style="font-size:12pt;">和</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">，如果存在</span><i><span style="font-size:12pt;">p</span></i><span style="font-size:12pt;">&lt;<i>N</i></span><span style="font-size:12pt;">，满足对于</span><i><span style="font-size:12pt;">i</span></i><span style="font-size:12pt;">=0,1,……<i>p</i>-1</span><span style="font-size:12pt;">，</span><i><span style="font-size:12pt;">S<sub>i</sub></span></i><span style="font-size:12pt;">=<i>T<sub>i</sub></i></span><span style="font-size:12pt;">且</span><i><span style="font-size:12pt;">S<sub>p</sub></span></i><span style="font-size:12pt;">&lt;<i>T<sub>p</sub></i></span><span style="font-size:12pt;">，我们称</span><i><span style="font-size:12pt;">S</span></i><span style="font-size:12pt;">比</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">字典序小。</span> 
</div>
<div style="margin:13pt 0cm;line-height:normal;">
<b><span style="font-size:large;"><span style="font-weight:normal;font-size:12pt;">【输入文件】</span></span></b> 
</div>
<p>
<span style="font-size:12pt;">输入文件</span><span style="font-size:12pt;">transform.in</span>
</p>
<p>
<span style="font-size:12pt;">第一行包含一个整数</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">，表示序列的长度。</span>
</p>
<p>
<span style="font-size:12pt;">接下来的一行包含</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">个整数</span><i><span style="font-size:12pt;">D<sub>i</sub></span></i><span style="font-size:12pt;">，其中</span><i><span style="font-size:12pt;">D<sub>i</sub></span></i><span style="font-size:12pt;">表示</span><i><span style="font-size:12pt;">i</span></i><span style="font-size:12pt;">和</span><i><span style="font-size:12pt;">T<sub>i</sub></span></i><span style="font-size:12pt;">之间的距离。</span>
</p>
<div style="margin:13pt 0cm;line-height:normal;">
<b><span style="font-size:large;"><span style="font-weight:normal;font-size:12pt;">【输出文件】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;">输出文件为</span><span style="font-size:12pt;">transform.out</span><span style="font-size:12pt;">。</span> 
</div>
<p style="text-indent:21pt;">
<span style="font-size:12pt;">如果至少存在一个满足要求的变换序列</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">，则输出文件中包含一行</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">个整数，表示你计算得到的字典序最小的</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">；</span>
</p>
<p style="text-indent:21pt;">
<span style="font-size:12pt;">否则输出</span><span style="font-size:12pt;">”No Answer”</span><span style="font-size:12pt;">（不含引号）。</span>
</p>
<p style="text-indent:21pt;">
<span style="font-size:12pt;"><u>注意：输出文件中相邻两个数之间用一个空格分开，行末不包含多余空格。</u></span>
</p>
<div style="margin:13pt 0cm;line-height:normal;">
<b><span style="font-size:large;"><span style="font-weight:normal;font-size:12pt;">【输入样例】</span></span></b> 
</div>
<div style="text-indent:21pt;">
<span style="font-size:12pt;">5</span> 
</div>
<div style="text-indent:21pt;">
<span style="font-size:12pt;">1 1 2 2 1</span> 
</div>
<div style="margin:13pt 0cm;line-height:normal;">
<b><span style="font-size:large;"><span style="font-weight:normal;font-size:12pt;">【输出样例】</span></span></b> 
</div>
<div style="text-indent:21pt;">
<span style="font-size:12pt;">1 2 4 0 3</span> 
</div>
<div style="margin:13pt 0cm;line-height:normal;">
<b><span style="font-size:large;"><span style="font-weight:normal;font-size:12pt;">【</span><span style="font-weight:normal;font-size:12pt;">数据规模和约定</span><span style="font-weight:normal;font-size:12pt;">】</span></span></b> 
</div>
<div style="layout-grid-mode:char;text-indent:20.5pt;">
<span style="font-size:12pt;color:blue;">20</span><span style="font-size:12pt;">%</span><span style="font-size:12pt;">的数据中</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">≤50</span><span style="font-size:12pt;">；</span> 
</div>
<div style="layout-grid-mode:char;text-indent:20.5pt;">
<span style="font-size:12pt;">60%</span><span style="font-size:12pt;">的数据中</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">≤500</span><span style="font-size:12pt;">；</span> 
</div>
<div style="text-indent:20.5pt;">
<span style="font-size:12pt;">100%</span><span style="font-size:12pt;">的数据中</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">≤10000</span><span style="font-size:12pt;">。</span> 
</div>
<p>
 
</p>
