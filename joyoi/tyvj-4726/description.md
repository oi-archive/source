# 

 
 # 题目描述 
<p><span style="color: rgb(0, 0, 0); font-family: &quot;Times New Roman&quot;; font-size: 14px; background-color: rgb(228, 240, 248);">铁索连环是三国杀中一种很有用的锦囊，其作用是改变角色的连环状态。每个角色只有两种状态，横置（表示被连环）与重置（表示没&nbsp;有被连环），当一名横置状态的角色受到属性伤害时，所有同时处于横置状态的角色也受到相同点数的伤害，然后改为重置状态。铁索&nbsp;连环的作用就是使指定m名角色的状态发生改变（横置变重置，重置变横置）。在一局三国杀中，Marvin疯狂地打出了n张铁索连环，他&nbsp;想要知道最终每名角色的状态。&nbsp;每名角色的状态用一个长度为m的字符串表示，1表示横置，0表示重置。初始状态下所有角色都处于重置状态。&nbsp;</span><img src="/source/joyoi/tyvj-4726/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDcyNi9odHRwOi8vNTkuNjEuNzUuNTo4MTg4L0p1ZGdlT25saW5lL2ltYWdlcy9kYXRhLzE0MjMvMS5HSUY=.GIF" style="color: rgb(0, 0, 0); font-family: &quot;Times New Roman&quot;; font-size: 14px;" /></p> 

 
 # 输入格式 
<p><span style="color: rgb(0, 0, 0); font-family: &quot;Times New Roman&quot;; font-size: 14px; background-color: rgb(228, 240, 248);">输入文件chain.in包含n+1行：&nbsp;第1行是整数n和m，(1&lt;=n&lt;=1000000&nbsp;,&nbsp;1&lt;=m&lt;=30)。&nbsp;第2行到第n+1行是一个长度为m的字符串，表示每张铁索连环影响的角色，0表示该角色不受影响，1表示该角色受到影响。</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(0, 0, 0); font-family: &quot;Times New Roman&quot;; font-size: 14px; background-color: rgb(228, 240, 248);">输出文件chain.out包含1行,为一个长度为m的字符串，表示最终角色的状态。</span></p> 
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
<tr><td>4 4
0101
1110
0001
0111</td><td>1101</td></tr></table>
