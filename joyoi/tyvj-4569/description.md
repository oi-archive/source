# 

 
 # 题目背景 
<p align="left"><strong>亚子</strong>：卢西安~怎么最近AL里面开始要输入验证码了呢。好麻烦哦QAQ</p>

<p align="left"><strong>西村</strong>：啊，那也没办法呀。亚子还是老老实实自己填吧。</p>

<p align="left"><strong>亚子</strong>：不嘛，帮帮我啦&gt;_&lt;。没关系，只要你1秒钟。</p> 

 
 # 题目描述 
<p style="line-height: 15pt; background-image: initial; background-attachment: initial; background-size: initial; background-origin: initial; background-clip: initial; background-position: initial; background-repeat: initial;"><span style="font-size:10.5pt;
font-family:&quot;Microsoft YaHei UI&quot;,&quot;sans-serif&quot;;color:black">最后西村还是答应了亚子的请求，但是他只对网络游戏比较熟，并不会编程。无奈之下他只好请你来帮忙解决这个问题。</span></p>

<p style="line-height: 15pt; background-image: initial; background-attachment: initial; background-size: initial; background-origin: initial; background-clip: initial; background-position: initial; background-repeat: initial;"><span style="font-size:10.5pt;
font-family:&quot;Microsoft YaHei UI&quot;,&quot;sans-serif&quot;;color:black"><span lang="EN-US">AL</span>界面下方给出的验证码是一张黑白图，亚子仅仅要求识别出图片中黑色部分所表示的数字，其中的数字只可能是<span lang="EN-US">1~9</span>。<span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 输入格式 
<p align="left">只包含一组数据。</p>

<p align="left">第一行为两个正整数：m,n分别表示图形的长、宽。</p>

<p align="left">第二行开始n行每行m个字符，对每个字符如果是&rsquo;.&rsquo;则表示此处是空白，否则表示此处是黑色的栅格。</p> 

 
 # 输出格式 
<p align="left">输出一行，即识别的结果。不会超过15个字符。</p> 

 
 # 提示 
<p align="left">测试数据建议在写字板或者记事本中观看，大数据观看时为了较好的效果可以把字体调成很小；样例大概在控制台程序下输入会有能够接受的格式。</p>

<p align="left">20%的数据,&nbsp;n,m&le;100。</p>

<p align="left">40%的数据,n&le;1080,m&le;1920。数字是Windows下常见的字体，用画图绘制而成，可能会加粗、斜体或缩放大小。</p>

<p align="left">20%的数据,n&le;1080,m&le;1920。数字是Windows下常见的字体，可能在上述基础上利用PhotoShop实现弯曲、旋转（不超过5&deg;）。</p>

<p align="left">20%的数据,n,m&le;1000。数字是shy在iPad中用触感笔手写生成。</p>

<p align="left">数据保证，尽量回避印刷体的1以防与7混淆。数据不会太难且书写比较规范，一般的人肉眼就可以辨别。</p>

<p align="left"><img alt="" src="/source/joyoi/tyvj-4569/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDU2OS9odHRwOi8vdHl2ai5jbi9BdmF0YXIvNDIyMDY=" style="width: 427px; height: 640px;" /></p>

<p align="left"><u>Thanks&nbsp;for&nbsp;viewing&nbsp;this&nbsp;problem.</u></p> 
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
<tr><td>68 8
....................................................................
.aaa....aaa............aaa......................aa.......Array......
a...a..a...a..........a...a....................a.............a......
a...a..a...a..........a...a...................a..............a......
.aaa....aaaa...........aaaa...................a.aaa.........C.......
a...a.....a...............a...................aa...a........a.......
a...a....a................a...................a....a........t.......
.aaa.....a...............a.....................aaaa.........s.......</td><td>89967</td></tr><tr><td>39 7
.......a......aaaaa.............a......
......aa......a.................a......
.....a.a......a.................a......
....a..a......aaaa..............a......
...aRusiana.......a.............a......
.......a..........a.............a......
.......a......aaaa..............a......</td><td>451</td></tr><tr><td>36 9
....................................
.....Ako.....aaa.....aaa....aaa.....
....a...a...a...a...a...a..a...a....
........a.......a.......a......a....
.......a......aa......aa.....aa.....
......a.........a.......a......a....
.....a......a...a...a...a..a...a....
....aaaaa....aaa.....aaa....aaa.....
....................................</td><td>2333</td></tr></table>
