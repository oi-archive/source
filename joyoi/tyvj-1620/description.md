# 

 
 # 题目背景 
经典的动归题&nbsp; 

 
 # 题目描述 
卡门——农夫约翰极其珍视的一条Holsteins奶牛——已经落了到“垃圾井”中。“垃圾井”是农夫们扔垃圾的地方，它的深度为D&nbsp;(2&nbsp;&lt;=&nbsp;D&nbsp;&lt;=&nbsp;100)英尺。<BR>卡门想把垃圾堆起来，等到堆得与井同样高时，她就能逃出井外了。另外，卡门可以通过吃一些垃圾来维持自己的生命。<BR>每个垃圾都可以用来吃或堆放，并且堆放垃圾不用花费卡门的时间。<BR>假设卡门预先知道了每个垃圾扔下的时间t(0&lt;t&lt;=1000)，以及每个垃圾堆放的高度h(1&lt;=h&lt;=25)和吃进该垃圾能维持生命的时间f(1&lt;=f&lt;=30)，要求出卡门最早能逃出井外的时间，假设卡门当前体内有足够持续10小时的能量，如果卡门10小时内没有进食，卡门就将饿死。<BR> 

 
 # 输入格式 
第一行为2个整数，D&nbsp;和&nbsp;G&nbsp;(1&nbsp;&lt;=&nbsp;G&nbsp;&lt;=&nbsp;100)，G为被投入井的垃圾的数量。<BR>第二到第G+1行每行包括3个整数：T&nbsp;(0&nbsp;&lt;&nbsp;T&nbsp;&lt;=&nbsp;1000)，表示垃圾被投进井中的时间；F&nbsp;(1&nbsp;&lt;=&nbsp;F&nbsp;&lt;=&nbsp;30)，表示该垃圾能维持卡门生命的时间；和&nbsp;H&nbsp;(1&nbsp;&lt;=&nbsp;H&nbsp;&lt;=&nbsp;25)，该垃圾能垫高的高度。<BR> 

 
 # 输出格式 
如果卡门可以爬出陷阱，输出一个整表示最早什么时候可以爬出；否则输出卡门最长可以存活多长时间。 

 
 # 提示 
卡门堆放她收到的第一个垃圾：height=9；<BR>卡门吃掉她收到的第二个垃圾，使她的生命从10小时延伸到13小时；<BR>卡门堆放第3个垃圾，height=19；<BR>卡门堆放第4个垃圾，height=20。<BR>slzxmxh 
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
<tr><td>20 4
5 4 9
9 3 2
12 6 10
13 1 1
</td><td>13</td></tr></table>
