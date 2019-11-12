# 题目描述


<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输入文件（freq.in）中有n个1至30的数字，统计并输出其中每个数字出现的频率，并输出到输出文件（freq.out）中，注意数字和百分比之间由冒号隔开，百分比精确到小数点后一位。</span> 
</div>
<div>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入格式】</span> 
</div>
<div>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">       </span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输入文件</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">(freq.in)</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">有若干行组成，第一行为一个整数</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">300000</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">；接下来有</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行，每一行有一个大于等于</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">小于等于</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">30</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的整数。</span> 
</div>
<div>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输出格式】</span> 
</div>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">    </span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输出文件</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">(freq.out)</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">有</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">30</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行，分别为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">到</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">30</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">这</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">30</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">个数出现的频率。</span> 
</p>
<div>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入输出样例】</span> 
</div>
<div>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输入文件名：</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">freq.in</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</div>
<div>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">5</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">20</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">8</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">26</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">20</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件名</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">：</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">freq.out</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1:20.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">2:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">3:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">5:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">6:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">7:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">8:20.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">9:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">10:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">11:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">12:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">13:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">14:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">15:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">16:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">17:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">18:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">19:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">20:40.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">21:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">22:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">23:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">24:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">25:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">26:20.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">27:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">28:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">29:0.0%</span> 
</div>
<div align="left">
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">30:0.0%</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</div>
