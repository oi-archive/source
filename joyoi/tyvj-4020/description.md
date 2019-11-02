# 

 
 # 题目背景 
<p>安徽2015&nbsp;第四道</p>

<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">滋贺县的琵琶湖享有盛名，尤其是湖中央的琵琶岛。</span></p>

<p><em>//本题由&nbsp;iostream&nbsp;提供</em></p> 

 
 # 题目描述 
<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">滋贺县的琵琶湖享有盛名，尤其是湖中央的琵琶岛。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">琵琶岛不仅外观上是矩形的，而且还被分割为了&nbsp;n&nbsp;x&nbsp;m&nbsp;的格子图。每一块格子区域都有着确定的高度。不幸的是，琵琶湖的水位最近开始上涨了，第&nbsp;i&nbsp;年湖面的高度将上涨至&nbsp;i&nbsp;米。另外一方面，琵琶岛是由松软的土质形成的，且琵琶湖的湖水可以自由渗入到其中。也就是说，如果有一块格子区域的高度不超过当前的水位，则将被淹没。相连的未被淹没的格子（有着公共边的格子区域）将组成一块未被淹没的区域。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">现在，小可可希望知道对于指定的某一年来说，琵琶岛被分割为了多少块未被淹没的区域。</p> 

 
 # 输入格式 
<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">输入的第一行有两个整数&nbsp;n&nbsp;和&nbsp;m，由一个空格隔开，表示琵琶岛的大小。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">之后&nbsp;n&nbsp;行，每行有&nbsp;m&nbsp;个正整数，在&nbsp;[1,10^9]&nbsp;范围内,表示了对应格子区域的高度。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">之后一行有一个整数&nbsp;T。再之后的一行，有&nbsp;T&nbsp;个整数&nbsp;t<em>j，满足&nbsp;0&lt;=t_1&lt;=t_2&lt;=...&lt;=t</em>{T-1}&lt;=t_T&lt;=10^9。</p> 

 
 # 输出格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">在输出中，你的程序应该输出单独一行，包含&nbsp;T&nbsp;个整数&nbsp;r_j&nbsp;以空格隔开。其中&nbsp;r_j&nbsp;表示了在第&nbsp;t_j&nbsp;年，未被淹没的区域的个数。</span></p> 
