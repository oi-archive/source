# 题目描述


<p>
【题目描述】
</p>
<p>
编程计算由“1”号围成的下列图形的面积。如下图所示，在10*10的二维数组中，有“1”围住了14个点，因此面积为14。
</p>
<p>
【输入文件】
</p>
<p>
10*10的0或1数字矩阵；
</p>
<p>
【输出文件】
</p>
<p>
符合题目要求的面积大小，如存在多个闭合区域（如样例所示），则累加面积；
</p>
<p>
【样例输入】
</p>
0 0 0 0 0 0 0 0 0 0<br/>
0 0 0 0 <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> 0 0 0<br/>
0 0 0 0 <strong><span style="background-color:#E53333;">1</span></strong> <span style="background-color:#009900;">0</span> <span style="background-color:#009900;">0</span> <strong><span style="background-color:#E53333;">1</span></strong> 0 0<br/>
0 0 0 0 0 <strong><span style="background-color:#E53333;">1</span></strong> <span style="background-color:#009900;">0</span> <span style="background-color:#009900;">0</span> <strong><span style="background-color:#E53333;">1</span></strong> 0<br/>
0 0 <strong><span style="background-color:#E53333;">1</span></strong> 0 0 0 <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> 0<br/>
0 <strong><span style="background-color:#E53333;">1</span></strong> <span style="background-color:#009900;">0</span> <strong><span style="background-color:#E53333;">1</span></strong> 0 <strong><span style="background-color:#E53333;">1</span></strong> <span style="background-color:#009900;">0</span> <span style="background-color:#009900;">0</span> <strong><span style="background-color:#E53333;">1</span></strong> 0<br/>
0 <strong><span style="background-color:#E53333;">1</span></strong> <span style="background-color:#009900;">0</span> <span style="background-color:#009900;">0</span> <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> <span style="background-color:#009900;">0</span> <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> 0<br/>
0 0 <strong><span style="background-color:#E53333;">1</span></strong> <span style="background-color:#009900;">0</span> <span style="background-color:#009900;">0</span> <span style="background-color:#009900;">0</span> <span style="background-color:#009900;">0</span> <strong><span style="background-color:#E53333;">1</span></strong> 0 0<br/>
0 0 0 <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> <strong><span style="background-color:#E53333;">1</span></strong> 0 0<br/>
0 0 0 0 0 0 0 0 0 0<br/>
<p>
【样例输出】
</p>
<p>
14
</p>
<p>
<br/>
</p>
