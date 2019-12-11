# 

 
 # 题目描述 
<p><img alt="" src="/source/joyoi/tyvj-4386/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDM4Ni9odHRwOi8vY2V4b3UuaW1nNDcud2FsOC5jb20vaW1nNDcvNTQzMjEyXzIwMTYwNDE1MTgzMDE5LzE0NjIxNjk3MTA3NS5wbmc=.png" style="width: 724px; height: 914px;" /></p> 

 
 # 输入格式 
<p>这是一道提交答案型试题，所有的输入文件opt*.in&nbsp;都已在目录下。</p>

<p>对于每个输入文件，文件第一行包含一个整数n，表示布尔变量的个数。第二行为一个整数m，为布尔表达式的个数。接下来m&nbsp;行，每行为一个布尔表达式，表达式格式同上述定义，并请参看输入文件（表达式中不含空格）。</p> 

 
 # 输出格式 
<p>对于每一个输入文件，你需要在对应目录下给出对应的输出文件（主文件名不变，扩展名为.out）。</p>

<p>输出文件包含n&nbsp;行，每行为0&nbsp;或1。第i&nbsp;行表示对第i&nbsp;个布尔变量的赋值(1表示赋值为True,&nbsp;0&nbsp;表示赋值为False).</p> 

 
 # 提示 
<p>在本题中输出任意的n行0或1均为合法输出。<br />
在本样例中若输出<br />
1<br />
1<br />
1<br />
则两个表达式均被满足；而若输出为<br />
0<br />
1<br />
1<br />
则仅有第二个表达式被满足；而若输出为<br />
1<br />
0<br />
0<br />
则没有表达式被满足。</p>

<p><a href="http://7xta2e.com2.z0.glb.clouddn.com/tyvj4386.zip">点击下载输入数据。</a></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3
2
x1&x2&x3
~x1|x2</td><td>1
1
1</td></tr></table>
