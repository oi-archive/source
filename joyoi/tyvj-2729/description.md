# 

 
 # 题目描述 
<p>
<br>科学家们在Samuel星球上的探险仍在继续。非常幸运的，在Samuel星球的南极附近，探险机器人发现了一个巨大的冰湖！机器人在这个冰湖中搜集到了许多RNA片段运回了实验基地。<br>科学家们经过几个昼夜的研究，发现这些RNA片段中有许多是未知的病毒！<br>每个RNA片段都是由A、C、T、G组成的序列。科学家们也总结出了Samuel星球上的“病毒模版片段”。一个模版片段是由A、C、T、G的序列加上通配符 * 和 ? 来表示。其中 * 的意思是可以匹配上0个或任意多个字符，而 ? 的意思是匹配上任意一个字母。<br>如果一个RNA片段能够和“病毒模版片段”相匹配，那么这个RNA片段就是未知的病毒。<br>例如，假设“病毒模版片段”为A*G?C。RNA片段：AGTC，AGTGTC都是未知的病毒，而RNA片段AGTGC则不是病毒。<br>由于，机器人搜集的这些RNA片段中除去病毒的其他部分都具有非常高的研究价值。所以科学家们希望能够分辨出其中哪些RNA片段不是病毒，并将不是病毒的RNA片段运回宇宙空间站继续进行研究。<br>科学家将这项任务交给了小联。现在请你为小联编写程序统计哪些RNA片段不是病毒。<br><br></p> 

 
 # 输入格式 
<p>
第一行有一个字符串，由A、C、T、G、*、? 组成。表示“病毒模版片段”。“病毒模版片段”的长度不超过1000。第二行有一个整数N（0<N<500），表示机器人搜集到的RNA片段的数目。随后的N行，每一行有一个字符串，由A、C、T、G组成，表示一个RNA片段。每个RNA片段的长度不超过500。注意：“病毒模版片段”和RNA片段的长度都至少为1。<br><br></p> 

 
 # 输出格式 
<p>
只有一行输出，为整数M，即不是病毒的RNA片段的数目。<br></p> 

 
 # 提示 
<p>
输入中的RNA片段AGTGC不是病毒。<br></p> 
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
<tr><td>A*G?C
3
AGTC
AGTGTC
AGTGC
</td><td>    1</td></tr></table>
