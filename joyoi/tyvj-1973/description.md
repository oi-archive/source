# 

 
 # 题目描述 
xuzhenyi的一家每天24小时营业的超市，需要一批出纳员来满足它的需要。超市经理雇佣你来帮他解决他的问题——超市在每天的不同时段需要不同数目的出纳员（例如：午夜时只需一小批，而下午则需要很多）来为顾客提供优质服务。他希望雇佣最少数目的出纳员。<br><br>经理已经提供你一天的每一小时需要出纳员的最少数量——R(0),&nbsp;R(1),&nbsp;...,&nbsp;R(23)。R（0）表示从午夜到上午1：00需要出纳员的最少数目，R（1）表示上午1：00到2：00之间需要的，等等。每一天，这些数据都是相同的。有N人申请这项工作，每个申请者I在没24小时中，从一个特定的时刻开始连续工作恰好8小时，定义tI&nbsp;（0&nbsp;&lt;=&nbsp;tI&nbsp;&lt;=&nbsp;23）为上面提到的开始时刻。也就是说，如果第I个申请者被录取，他（她）将从tI&nbsp;时刻开始连续工作8小时。<br><br>你将编写一个程序，输入R（I）（I&nbsp;=&nbsp;0..23）和tI&nbsp;（I&nbsp;=&nbsp;1..N），它们都是非负整数，计算为满足上述限制需要雇佣的最少出纳员数目。在每一时刻可以有比对应的R（I）更多的出纳员在工作。 

 
 # 输入格式 
输入文件的第一行为测试点个数（&lt;=&nbsp;20）。每组测试数据的第一行为24个整数表示R（0），R（1），...，&nbsp;R（23）（R（I）&lt;=&nbsp;1000）。接下来一行是N，表示申请者数目（0&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;1000），接下来每行包含一个整数tI&nbsp;（0&nbsp;&lt;=&nbsp;tI&nbsp;&lt;=&nbsp;23）。两组测试数据之间没有空行。 

 
 # 输出格式 
对于每个测试点，输出只有一行，包含一个整数，表示需要出纳员的最少数目。如果无解，你应当输出“No&nbsp;Solution”。 

 
 # 提示 
huyichen 
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
1 0 1 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1
5
0
23
22
1
10</td><td>1</td></tr></table>
