# 

 
 # 题目背景 
石家庄二中&nbsp;神探狄仁杰杯NOIP模拟赛&nbsp;第一试&nbsp;第三题&nbsp;2011.10<BR><BR>幽蓝中带绿，跳动如蛇芯。<BR>阴森映魅影，千里外冥明。<BR>——蛇灵祭坛的魔火是这个组织的圣物，它是蛇灵总坛权力的象征。<BR> 

 
 # 题目描述 
狄仁杰率领大军开进大杨山，拔除了所有蛇灵用于通风报信的侦查口——蛇穴，准备部署进攻方案。<BR>由于蛇灵总坛建设在巨大的齿轮盘上，启动机关消息掣后，总坛入口陀罗地立即遍布机关，所以大军只能分开从蛇穴进入。大杨山中蛇穴众多并且狭小，所以当前大军比较分散。假设大军分为N支队伍，分布在N个蛇穴口，每支队伍都有一位领军将领。为了集中到蛇灵总坛，队伍A要么到队伍B所在的蛇穴口处进入（如果A和B蛇穴口之间有路相通），并且转由队伍B的领军将领负责领导，要么仍由本队伍的领军将领领导直接行进到蛇灵总坛。<BR>但是狄仁杰不可能对这么多领军将领一起发号施令，所以他要求：到达蛇灵总坛时，大军最多只能有K位领军将领来领导。现在给你一张有N+1个点(代表蛇穴和总坛)，M条边(代表道路)的加权无向图，要你求出所有队伍到达总坛的最短总路程。<BR> 

 
 # 输入格式 
第一行是整数M，接下来M行描述了M条道路。每行形式如同：S1&nbsp;S2&nbsp;x，S1和S2均是一个长度不超过10的字符串（姑且认为蛇灵的蛇穴都是英文名称=&nbsp;=|），表示该道路连接的两个蛇穴的名称，中间用一个空格隔开，x表示这条道路的长度。最后一行包含一个整数k，到达蛇灵总坛时领军将领个数的限制。名称为Park的字符串代表蛇灵总坛。<BR>输入数据保证图的连通性。<BR> 

 
 # 输出格式 
仅一行，形式如同：Total&nbsp;miles&nbsp;driven:&nbsp;xxx。xxx是整数，表示最短总路程。 

 
 # 提示 
对于50%的数据，1&lt;=M&lt;=20<BR>对于100%的数据，1&lt;=K&lt;=N&lt;=20，1&lt;=M&lt;=400，1&lt;=X&lt;=1000<BR>石家庄二中&nbsp;神探狄仁杰杯NOIP模拟赛&nbsp;第一试&nbsp;第三题&nbsp;2011.10<BR>题目从POJ改编，非原创 
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
<tr><td>10
Alphonzo Bernardo 32
Alphonzo Park 57
Alphonzo Eduardo 43
Bernardo Park 19
Bernardo Clemenzi 82
Clemenzi Park 65
Clemenzi Herb 90
Clemenzi Eduardo 109
Park Herb 24
Herb Eduardo 79
3
</td><td>Total miles driven: 183</td></tr></table>
