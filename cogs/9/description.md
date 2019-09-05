# 题目描述


<h3>
<b>【题目描述】</b> 
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">n个城市之间有通讯网络，从这n个城镇中选定几座城镇，在那里建立中心台站，要求它们与其它各城镇相邻，同时为降低造价，要使中心台站数目最少。</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
<span style="color:inherit;font-size:16px;font-weight:normal;font-family:inherit;background-color:white;">输入文件有若干行</span> 
</p>
<p>
<span style="color:inherit;font-family:inherit;">第一行，一个整数n，表示共有n个城市$(2&lt;=n&lt;=100)$</span> 
</p>
<p>
下面有n行,每行有n个数字。第p行第q列的数字表示城镇p与城镇q之间有无直接通讯线路。数字为1表示有，0表示无。
</p>
<h3>
【输出格式】
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">输出文件有若干行</span> 
</p>
<p>
第一行，1个整数a，表示最少中心台站数目。
</p>
<p>
第二行一个整数b,表示共有b种方案。下面有b行，每行有a个整数，表示一种建站方案。多种方案输出时，输出顺序按城镇编号由小到大字典序输出。
</p>
<h3>
【样例输入】
</h3>
<pre>6
0 1 1 1 0 0
1 0 0 1 0 0
1 0 0 0 1 0
1 1 0 0 0 1
0 0 1 0 0 1
0 0 0 1 1 0
</pre>
<h3>
【样例输出】
</h3>
<pre>2
5
1 5
1 6
2 5
3 4
4 5
</pre>
