# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在noip2009中，yuan0818神牛经过3个小时的激烈拼杀，终于进入了省队。回到保定后，我们决定为他庆祝一下。经过我们的一翻唇枪舌战，终于说服yuan0818带他的GF来了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;保定二中高一的oier们老早就得到了这个消息，他们布下了天罗地网，准备"抓"到yuan0818让他请客,当然吝啬的yuan0818怎么会自己请客呢,他准备在不被高一的oier发现的情况下找到GF并带她溜出学校.这样,一场"英雄救美"的好戏就此展开了.<BR>&nbsp;&nbsp;&nbsp;&nbsp;学校可以看成是一个N*N的矩阵,每个单位格子中都有一个数字X或一个字符<BR>&nbsp;&nbsp;&nbsp;&nbsp;如果这个格子中是数字X那么<BR>&nbsp;&nbsp;&nbsp;&nbsp;X&lt;-1&nbsp;表示这个地方是墙,<BR>&nbsp;&nbsp;&nbsp;&nbsp;X=-1&nbsp;表示这个地方有一个高一的oier，他可以发现他前后左右一个单位长度的目标<BR>&nbsp;&nbsp;&nbsp;&nbsp;X&gt;0,X&lt;=M&nbsp;表示这个地方有一个坚硬度为X的门<BR>&nbsp;&nbsp;&nbsp;&nbsp;X&gt;M&nbsp;表示这个地方有一把可以砸烂坚硬度小于等于X-M的门的锤子;<BR>&nbsp;&nbsp;&nbsp;&nbsp;如果这个格子中不是数字而是一个G,就表示yuan0818的GF在这个位置。为了简化题目,我们规定yuan0818的GF在(n,n),且只有一个GF<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在yuan0818在(1,1)位置,那么他怎样才能用最少的步数才能找到他的GF呢?<BR>&nbsp;&nbsp;&nbsp;&nbsp;当然yuan0818不能大摇大摆地进去,因为他不能被高一的oier发现.yuan0818最多可以同时拿着N*N把锤子,不过如果他的锤子的等级与他要砸烂的门的等级的绝对值&gt;1,那他就会被警觉的高一的oier发现,这样yuan0818就必须得请客了~&nbsp;~(当然,我们的yuan0818神牛不会让此事发生的,如果一定要这样的话,他宁可不去找他的GF);<BR> 

 
 # 输入格式 
第一行两个数&nbsp;N&nbsp;,&nbsp;M&nbsp;如题所述<BR>接下来是一个&nbsp;N*N&nbsp;的矩阵，描述学校的情况<BR> 

 
 # 输出格式 
一个数，最少的步数.如果yuan0818不得不请客或他怎么都到不了他的GF那里,那么就输出-1; 

 
 # 提示 
&nbsp;&nbsp;1.十六班的巨菜cannot为膜拜十八班的神牛yuan0818编写的题目<BR>&nbsp;&nbsp;2.以上故事纯属虚构，但传承至今，是一个非常有名的神话故事。<BR>&nbsp;&nbsp;3.数据范围：<BR>&nbsp;&nbsp;对于20%的数据不会有高一的oier出现且只有一种斧子和一种门;<BR>&nbsp;&nbsp;对于30%的数据&nbsp;,&nbsp;有&nbsp;N&nbsp;&lt;=&nbsp;10&nbsp;M&nbsp;&lt;=&nbsp;4;<BR>&nbsp;&nbsp;对于50%的数据&nbsp;,&nbsp;有&nbsp;N&nbsp;&lt;=&nbsp;20&nbsp;M&nbsp;&lt;=&nbsp;10;<BR>&nbsp;&nbsp;对于100%的数据,&nbsp;有&nbsp;N&nbsp;&lt;=&nbsp;40&nbsp;M&nbsp;&lt;=&nbsp;14&nbsp;有K1种斧子,K2种门,K3个高一的oier,所有斧子的标号不会超过31,且在各组数据中不会超过M*2<BR> 
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
<tr><td>2 0
0 0
0 G
</td><td>2</td></tr></table>
