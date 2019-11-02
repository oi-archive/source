# 

 
 # 题目描述 
<p>
在4*4的16间房间里有一盏灯，这些房间共有12个开关（如下图，开关用¤表示），为了方便起见，开关号与房间号一致。每个开关控制若干盏灯，开关动作一次，相应被控制的等状态取反一次，即亮的变暗，暗的变亮（0表示暗，1表示亮）。用四位16进制数码表示一个状态（如图$E3D7）。现在用$0660为目标状态，要求找到一条从任意状态到目标状态的最佳路径。<br><br><center><img src="/source/joyoi/tyvj-2853/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjg1My9wcm9ibGVtc19pbWFnZXMvMzM5MS9wZy5qcGc=.jpg"></img></center></p> 

 
 # 输入格式 
<p>
在输入文件中的第一行为一个整数N，表示有下面有N种初始状态，以下的N行，每一行为一个4位十六进制数，表示一种初始状态。</p> 

 
 # 输出格式 
<p>
在输出文件的每一行。分别输出每个输出状态达到目标状态，所按开关的顺序，开关的编号为十六进制表示，也就是说开关10用A，开关12用C，开关14用E，开关15用F表示，如结果为2CF，表示开关序列为2，12，15，开关的顺序按字典顺序输出。</p> 
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
<tr><td>1
246B
</td><td>ACEF</td></tr></table>
