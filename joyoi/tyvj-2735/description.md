# 

 
 # 题目描述 
<p>
监狱（prison.pas/c/cpp）<br><br>【问题描述】<br><br>　　Q王国中有一个奇怪的监狱，这个监狱一共有P个牢房，这些牢房一字排开，第j个紧挨着第j+1个（最后一个除外）。现在正好牢房是满的。<br><br>　　上级下发了一个释放名单，要求每天释放名单上的一个。这可把看守们吓得不轻，因为看守们知道，现在牢房中的P个人，可以相互之间传话。如果某人离开了，那么原来和这个人能说话的人，都会很气愤，导致他们那天会一直大吼大叫，搞得看守很头疼。如果给这些要发火的人吃上肉，他们会安静点。<br><br>　　现在看守们想知道，如何安排释放的顺序，才能使得他们花费的肉钱最少。<br><br></p> 

 
 # 输入格式 
<p>
输入文件prison.in<br>第一行两个数P和Q，Q表示释放名单上的人数；<br>第二行Q个数，表示要释放哪些人。<br></p> 

 
 # 输出格式 
<p>
输出文件prison.out<br>仅一行，表示最少要给多少人次送肉吃。</p> 

 
 # 提示 
<p>
数据规模：<br>1=< P <=1000,1=< Q <=100<br></p> 
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
<tr><td>20 3
3 6 14</td><td>35</td></tr></table>
