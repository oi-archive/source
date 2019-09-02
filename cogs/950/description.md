
<p class="MsoNormal">
<span style="font-family:宋体;">
# 问题描述</b>



# 输入格式


<p class="MsoNormal">
<span lang="EN-US">输入文件第一行有一个正整数T，T&lt;=20，表示接下来有T个测试数据。<br/>
每个测试数据的第一行有一个正整数N，N&lt;=30000，表示实心矩形的数目，接下来有N行，每行有4个非负整数：x1,y1,x2,y2，表示对应矩形的左下角及右上角坐标，</span>满足x1&lt;x2且y1&lt;y2；接下来有一个正整数Q，Q&lt;=30000，表示线段的数目，接下来有Q行，每一行有4个非负整数：x3,y3,x4,y4，分别表示对应线段的两个端点坐标，其中x3&lt;x4且y3=y4。<span lang="EN-US"> </span> 
</p>

# 输出格式


<p class="MsoNormal">
   对于每个测试数据，输出有一行，包含一个整数，即被这些线段切割到的实心矩形总数。
</p>
<p class="MsoNormal">
【输入样例】
</p>
<p class="MsoNormal">
cutting.in<br/>
1<br/>
3<br/>
1 1 3 4<br/>
2 3 4 5<br/>
5 1 6 
3<br/>
5<br/>
0 1 6 1<br/>
0 3 6 3<br/>
0 5 6 5<br/>
0 5 2 5<br/>
0 6 2 6
</p>
<p>
cutting.out<br/>
7
</p>
