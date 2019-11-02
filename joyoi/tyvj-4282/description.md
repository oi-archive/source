# 

 
 # 题目背景 
<p>xzj希望打造一个灰常文明的群，所以对于每句话中的脏话换成*输出。脏话有38，250，BT，TMD，PIG，SHIT，FUCK。若没有一个脏字，则此人文明。否则不文明。对于有重叠部分的脏话需全部替换。</p> 

 
 # 输入格式 
<p>一个字符串，只有大写字母，数字和空格。</p> 

 
 # 输出格式 
<p>第一行：修改后的字符串。</p>

<p>第二行：是否文明（YES或NO）。</p> 
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
<tr><td>LUOWEIYE IS NOT ONLY A PIG BUT ALSO A 250</td><td>LUOWEIYE IS NOT ONLY A *** BUT ALSO A ***
NO</td></tr><tr><td>5QSHITMD3VBTMDML52BT7T2BTB569D64JK2BBEE93 9A6XBK29 5 P0MQ OJ 3HWI 51VTMDR BGPW45Y1TMDV5BFUCK00DBT
</td><td>5Q******3V****ML5***7T***B569D64JK**BEE93 9A6XBK29 5 P0MQ OJ 3HWI 51V***R BGPW45Y1***V5B****00D**
NO
</td></tr></table>
