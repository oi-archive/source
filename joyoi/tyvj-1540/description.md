# 

 
 # 题目描述 
7月17日是Mr.W的生日，ACM-THU为此要制作一个体积为N*pi的M层生日蛋糕，每层都是一个圆柱体。&nbsp;设从下往上数第i(1&nbsp;&lt;=&nbsp;i&nbsp;&lt;=&nbsp;M)层蛋糕是半径为Ri,&nbsp;高度为Hi的圆柱。当i&nbsp;&lt;&nbsp;M时，要求Ri&nbsp;&gt;&nbsp;Ri+1且Hi&nbsp;&gt;&nbsp;Hi+1。&nbsp;由于要在蛋糕上抹奶油，为尽可能节约经费，我们希望蛋糕外表面（最下一层的下底面除外）的面积Q最小。&nbsp;令Q&nbsp;=&nbsp;S*pi&nbsp;请编程对给出的N和M，找出蛋糕的制作方案（适当的Ri和Hi的值），使S最小。（除Q外，以上所有数据皆为正整数） 

 
 # 输入格式 
每组数据两行，第一行为N（N&nbsp;&lt;=&nbsp;10000），表示待制作的蛋糕的体积为N*pi；第二行为M(M&nbsp;&lt;=&nbsp;20)，表示蛋糕的层数为M。 

 
 # 输出格式 
仅一行，是一个正整数S（若无解则S=0）。<BR> 

 
 # 提示 
给大家提高AC率。NOIP99 
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
<tr><td>100
2
</td><td>68
</td></tr></table>
