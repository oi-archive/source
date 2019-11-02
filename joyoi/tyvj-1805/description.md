# 

 
 # 题目描述 
小刚在玩JSOI提供的一个称之为“建筑抢修”的电脑游戏：<BR><BR>经过了一场激烈的战斗，T部落消灭了所有z部落的入侵者。但是T部落的基地里已经有N个建筑设施受到了严重的损伤，如果不尽快修复的话，这些建筑设施将会完全毁坏。<BR>&nbsp;&nbsp;&nbsp;&nbsp;<BR>现在的情况是：T部落基地里只有一个修理工人，虽然他能瞬间到达任何一个建筑，但是修复每个建筑都需要一定的时间。同时，修理工人修理完一个建筑才能修理下一个建筑，不能同时修理多个建筑。如果某个建筑在一段时间之内没有完全修理完毕，这个建筑就报废了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;你的任务是帮小刚合理的制订一个修理顺序，以抢修尽可能多的建筑。<BR> 

 
 # 输入格式 
第一行是一个整数N，接下来N行每行两个整数T1,T2描述一个建筑：修理这个建筑需要T1秒，如果在T2秒之内还没有修理完成，这个建筑就报废了。 

 
 # 输出格式 
输出一个整数S，表示最多可以抢修S个建筑。 

 
 # 提示 
N&lt;150000，T1&lt;T2&lt;2^31。 
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
<tr><td>4
100 200
200 1300
1000 1250
2000 3200
</td><td>3</td></tr></table>
