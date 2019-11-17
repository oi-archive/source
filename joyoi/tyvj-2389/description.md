# 

 
 # 题目描述 
<p>
Johnny 在生日时收到了一件特殊的礼物，这件礼物由一个奇形怪状的管子和一些盘子组成. 这个管子是由许多不同直径的圆筒(直径也可以相同) 同轴连接而成. 这个管子的底部是封闭的,顶部是打开的. 下图是由直径为: 5cm, 6cm, 4cm, 3cm, 6cm, 2cm and 3cm 的圆筒组成的管子. <br><img border="0" src="/source/joyoi/tyvj-2389/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM4OS9wcm9ibGVtc19pbWFnZXMvMjc4NS8xNTEwXzEuanBn.jpg"><br>每个圆筒的高度都是相等的, 玩具中所带的盘子也是一些高度和它们相同的圆筒,直径有大有小. <br>Johnny 发明了一种游戏,把盘子从管子顶部一个接一个的扔下去,他想知道最后这些盘子落在了哪,假设盘子落下过程中圆心和管子的轴一直保持一致,比如说我们丢下去三个盘子: 3cm, 2cm and 5cm, 下图展示了最终它们的停止位置: <br><img border="0" src="/source/joyoi/tyvj-2389/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM4OS9wcm9ibGVtc19pbWFnZXMvMjc4NS8xNTEwXzIuanBn.jpg"><br>如图可以知道,盘子掉下去以后,要么被某个圆筒卡住,要么就是因为掉在了以前的一个盘子上而停住. <br>Johnny 想知道他最后扔下去的那个盘子掉在了哪个位置,你来帮他把. <br></p> 

 
 # 输入格式 
<p>
第一行两个整数 n 和 m ( 1<= n, m<= 300 000) 表示水管包含的圆筒数以及盘子总数. <br>第二行给出 n 个整数 r1, r2,...,rn ( 1 <=ri<= 1 000 000 000  for 1<= i<= n) 表示水管从上到下所有圆筒的直径. 第三行给出m 个整数k1, k2,..., km ( 1<= kj<= 1 000 000 000 for 1<= j<= m) 分别表示Johnny 依次扔下去的盘子直径. <br></p> 

 
 # 输出格式 
<p>
一个整数输出最后一个盘子掉在了哪一层,如果盘子不能扔进水管,那么打印0. <br></p> 
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
<tr><td>7 3
5 6 4 3 6 2 3
3 2 5
</td><td>2</td></tr></table>
