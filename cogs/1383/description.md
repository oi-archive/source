# 题目描述


<p>
</p><p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:宋体;">同一时刻有</span><span style="font-size:12.0pt;">N</span><span style="font-size:12.0pt;font-family:宋体;">位车主带着他们的爱车来到了汽车维修中心。维修中心共有</span><span style="font-size:12.0pt;">M</span><span style="font-size:12.0pt;font-family:宋体;">位技术人员，不同的技术人员对不同的车进行维修所用的时间是不同的。现在需要安排这</span><span style="font-size:12.0pt;">M</span><span style="font-size:12.0pt;font-family:宋体;">位技术人员所维修的车及顺序，使得顾客平均等待的时间最小。</span><span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:宋体;">说明：顾客的等待时间是指从他把车送至维修中心到维修完毕所用的时间。</span><span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:宋体;">输入</span></b><b><span style="font-size:12.0pt;"></span></b>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal" style="text-indent:21.0pt;">
<span style="font-size:12.0pt;font-family:宋体;">第一行有两个数</span><span style="font-size:12.0pt;">M,N</span><span style="font-size:12.0pt;font-family:宋体;">，表示技术人员数与顾客数。</span><span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal" style="text-indent:21.0pt;">
<span style="font-size:12.0pt;font-family:宋体;">接下来</span><span style="font-size:12.0pt;">n</span><span style="font-size:12.0pt;font-family:宋体;">行，每行</span><span style="font-size:12.0pt;">m</span><span style="font-size:12.0pt;font-family:宋体;">个整数。第</span><span style="font-size:12.0pt;">i+1</span><span style="font-size:12.0pt;font-family:宋体;">行第</span><span style="font-size:12.0pt;">j</span><span style="font-size:12.0pt;font-family:宋体;">个数表示第</span><span style="font-size:12.0pt;">j</span><span style="font-size:12.0pt;font-family:宋体;">位技术人员维修第</span><span style="font-size:12.0pt;">i</span><span style="font-size:12.0pt;font-family:宋体;">辆车需要用的时间</span><span style="font-size:12.0pt;">T</span><span style="font-size:12.0pt;font-family:宋体;">。</span><span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;font-family:宋体;">输出</span><span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:宋体;">最小平均等待时间，答案精确到小数点后</span><span style="font-size:12.0pt;">2</span><span style="font-size:12.0pt;font-family:宋体;">位。</span><span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;font-family:宋体;">样例</span><span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;">repair.in</span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;">2 2</span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;">3 2</span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;">1 4</span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;">repair.out</span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;">1.50</span>
</p>
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span>
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:宋体;">数据范围</span></b><b><span style="font-size:12.0pt;">:</span></b>
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;"></span></b>
</p>
<p class="MsoNormal" style="text-indent:21.0pt;">
<span style="font-size:12.0pt;">(2&lt;=M&lt;=9,1&lt;=N&lt;=60), (1&lt;=T&lt;=1000)</span>
</p>
<p></p>
