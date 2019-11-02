# 

 
 # 题目背景 
APIO2011&nbsp;T3<BR> 

 
 # 题目描述 
“猜单词”是一个双人游戏，在伊朗的青年学生中广为流行。假设有两个游戏者A和B，A作为先手，首先在一个双方都知道的语料库中选出一个单词，并记在脑海中。随后，他在一张小纸片上划下与单词字母数相等的小横线（不妨设为n条）。&nbsp;<BR>接下来，B尝试猜出这个单词。每一轮，B选择一个字母并告诉A。A按如下规则回应：&nbsp;<BR>若B所说的字母在单词中出现，A就把它写在对应的横线上。如果整个单词已经完整（所有的字母已经被猜出），B获胜。&nbsp;<BR>否则，如果字母没有在单词中出现，A就把它写在最左侧的下方仍为空白的横线下。如果所有横线下的空白处都已经有字母（也就是说，在这一轮前B已经猜了n个错误字母），那么B就输了，A获胜。&nbsp;<BR><BR>例如，A从语料库中选出了单词RED，且B已经依次猜了字母A,&nbsp;E,&nbsp;C,&nbsp;D,&nbsp;B和R。每一步的结果都在下图中展现。最终B获胜。但如果B在最后一步猜了S而不是R，他就输了。&nbsp;<BR><img src="/source/joyoi/tyvj-1734/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTczNC9Qcm9ibGVtSW1nLzE3MzQuanBn.jpg" border=0 align=middle><BR>Aidin是猜单词游戏迷。他相信，如果给定的语料库足够大，且其中的单词相对好，那么玩家A（先手）可以采取一种不公平的行动——修改选择的单词。也就是说，既然玩家A只将单词记在脑海中而不写下来，那他能够在游戏过程中随时变化这个单词，只要使得和当前已经给出的结果仍然一致即可。例如，在上面的游戏中，如果单词RED,&nbsp;BED,&nbsp;LED和TED都在语料库中，那么在第4步之后，A就可以确信他将胜利。他将总是把B给出的字母写在横线下（也就是认定其为错误的字母），那么每一次他将至多在集合&nbsp;{RED,&nbsp;BED,&nbsp;LED,&nbsp;TED}&nbsp;中失去一个备选单词。最终他将向B宣布：“这个单词是，嗯，……”，然后在他的集合中说出一个剩下的单词。&nbsp;<BR>Aidin想，如果语料库足够好，那么A甚至可能在游戏一开始就确定获胜。例如，如果选择的单词长度为2，而集合{ME,&nbsp;MD,&nbsp;DE,&nbsp;ED,&nbsp;AS,&nbsp;IS,&nbsp;AI,&nbsp;SI}中的单词都在语料库中，那么A总能获胜。请自己找出A获胜的策略。&nbsp;<BR>给定一个语料库，Aidin想知道是否无论B如何进行游戏，玩家A一定能获胜？&nbsp;<BR>请注意在任何一次游戏结束时，如果A获胜，A需要能够给出一个语料库中的单词作为被选出的单词，这个单词应当与A所有给出的回答一致。<BR> 

 
 # 输入格式 
输入包含若干个语料库。每个语料库应该被独立地处理。<BR>输入的第一行是一个整数C，代表语料库的数目。随后C个语料库以C个模块的形式出现在输入中。每两个模块之间以一个空行隔开。1&nbsp;≤&nbsp;C&nbsp;≤&nbsp;20。<BR>对于每个输入模块，第一行包含一个正整数k，表示语料库中单词的个数。接下来的若干行中包含k个单词。相邻的单词以空格、制表符或换行符分隔。每个单词由小于7个大写英语字母组成。<BR>每个单词都由不同的字母组成，也就是说，同一个字母在一个单词中出现的次数不会超过1次。 

 
 # 输出格式 
对于每个语料库，如果玩家A有必胜策略（也就是说，不论B按什么方法猜，A总能获胜），输出一行“Yes”。否则输出一行“No”。输出不包含引号。 

 
 # 提示 
对于20%的测试数据，k&nbsp;≤&nbsp;100，每个单词的长度不超过3；<BR>对于50%的测试数据，k&nbsp;≤&nbsp;300，每个单词的长度不超过4；<BR>对于所有测试数据中，k&nbsp;≤&nbsp;1000。 
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
<tr><td>2
12
SI ME AND AI ARE MD AS WHEN ED IS DE
HAPY

5
A B AB AC AD</td><td>Yes
No</td></tr></table>
