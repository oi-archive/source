# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;｛*总背景*｝<BR>&nbsp;&nbsp;&nbsp;&nbsp;公元3003年2月，Summer联盟对Winter联盟展开挑衅，公元3003年8月Summer依然难以攻破Winter。<BR>&nbsp;&nbsp;&nbsp;&nbsp;双方的战争在此时开始停歇，大家都想让士兵休息一下。10月，Summer联盟宣布暂时停战，Winter联盟也表示，如果Summer再次发动冲锋，Winter联盟将全面与Summer宣战。<BR>&nbsp;&nbsp;&nbsp;&nbsp;{总背景完}<BR>&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;已经年过六旬的HF感到十分急躁，他一生攻占别的星球时，无论大小，都没有能过抵挡的。之前乘风破浪的战争与现在的持久战形成了巨大的反差。HF也明显地感到，手下的将士们也开始有退却的意思。之前大量的战士以血肉之躯换来的——似乎只有失败。HF开始恐惧，他害怕一个个手下将士都死去。May,June,July这三个英勇的将士陪伴着HF走了多少岁月，但是May已经死了，他死的时候说：“不要再打下去了，我们会输的！”<BR>&nbsp;&nbsp;&nbsp;&nbsp;可是晚年的HF更害怕的是失败，所以，他作出了一个重大的决定：将Summer威力最大的三颗核弹中的一颗投向前方战场。这个决定会是正确还是错误的，等待时间来验证吧！<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;虽然这颗核弹的威力巨大，但是对于巨大的Winter联盟，这颗核弹还是不能够完全覆盖住整个Winter。HF决定攻击敌人的能量供给区：Winter的能量网络。<BR>&nbsp;&nbsp;&nbsp;&nbsp;Winter的能量网络有n*n个发电站组成，每个发电站有一个发电值power[i,j]，这形成n行n列的能量网络，这个网络的外围是一个巨大的能量屏障。<BR>&nbsp;&nbsp;&nbsp;&nbsp;因为从前这个能量屏障是无法破解的，所以Summer联盟从来没有在意它，但是这次Summer联盟的科学家已经完全找到了破解它的方法，用高吸附性的物质碳纳暂时破解能量屏障！可是这也只能暂时破解能量屏障，所以在核弹爆炸的时候这个能量屏障依然存在，它会对核弹的爆炸产生巨大的影响。<BR>&nbsp;&nbsp;&nbsp;&nbsp;核弹的爆炸范围有k*k，也就是说，在一个k*k矩阵内所有的发电站会被彻底摧毁，但是前面提到过，能量屏障是不可忽视的，虽然能量屏障原来是用来保护能量网络，但是现在却协助了核弹的杀伤！具体来说，由于核弹可能落在能量网络的边界，所以不可避免的会有爆炸冲向边界，涌向能量屏障。这时，能量屏障会产生不可思议的效果（正是这个效果以前严密地保护了能量网络）：它会把所有爆炸的辐射和微粒传送到对面（比如辐射攻击了上面，那么它会传送到下面{上对下，左对右}），并以原来的威力扩散。<BR>&nbsp;&nbsp;&nbsp;&nbsp;比如说，原网络是3*3的，爆炸的范围是2*2。那么当把核弹的左上角设定在第2行第3列，它会攻击到4个发电站：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.第二行第一列&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//后文的第三攻击值<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.第二行第三列（爆炸左上角）//后文的第一攻击值<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.第三行第一列&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//后文的第四攻击值<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.第三行第三列&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//后文的第二攻击值&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;<img src="/source/joyoi/tyvj-1638/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTYzOC9wcm9ibGVtaW1nLzE2MzgtMS5qcGc=.jpg" border=0 align=middle><BR>&nbsp;&nbsp;&nbsp;&nbsp;特别地，如果一个爆炸范围超过了右边界和下边界，那么它会被双重反弹，比如攻击范围超过了右边界1，下边界1（如样例），那么它会攻击到能量网络最左上的那个发电站。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在的任务是要你找到最佳的攻击方案。<BR>&nbsp;&nbsp;&nbsp;&nbsp;两个攻击方案的比较方法很特别，应当先比较两种攻击方案破坏的左上角的发电值（上文的第一攻击值），再比较左上角的下面一个发电值（上文的第二攻击值）……（不停往下，依次类推）再比较左上角的右边一个……（也就是一列列的扫）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;当比较到一个发电值不同时，我们认为攻击发电值较大的攻击方案更优。<BR>&nbsp;&nbsp;&nbsp;&nbsp;你只要找到这个最优方案应该设定的地点即可。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行两个正整数n,k，表示能量网络的大小和爆炸范围的大小。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来2~n+1行每行n个数，第i+1行第j个数表示第i行第j列的发电厂的发电值power[i,j]。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;两个数x,y，中间用一个空格隔开，表示最优方案应当是把核弹的左上角设定在(x,y)（第x行，第y列，即第一攻击值为power[x,y]）。<BR> 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;样例可以攻击到所有发电值为2的发电厂。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/source/joyoi/tyvj-1638/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTYzOC9wcm9ibGVtaW1nLzE2MzgtMi5qcGc=.jpg" border=0 align=middle><BR>&nbsp;&nbsp;&nbsp;&nbsp;20%的数据：1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;80<BR>&nbsp;&nbsp;&nbsp;&nbsp;100%的数据：1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;200&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;power[i,j]&nbsp;&lt;=&nbsp;10^9<BR>&nbsp;&nbsp;&nbsp;&nbsp;正坐在总指挥室的HF忽然想起了什么，他的军事才能好像在警告他。<BR>&nbsp;&nbsp;&nbsp;&nbsp;核弹操作室里……<BR>&nbsp;&nbsp;&nbsp;&nbsp;“现在发射吗？”设计师因紧张而发红的脸转向Summer联盟副指挥MJJ。<BR>&nbsp;&nbsp;&nbsp;&nbsp;“攻击吧！”MJJ握紧了拳头，“打掉他们的能源。”<BR>&nbsp;&nbsp;&nbsp;&nbsp;设计师颤抖的手伸向了那个标着“请慎按”的按钮，“等等！”HF冲进了核弹操作室，“也现在还不是最好的时候，再等等吧！”<BR>&nbsp;&nbsp;&nbsp;&nbsp;到底HF这个在军事天才是延误了战机还是拯救了自己？<BR>&nbsp;&nbsp;&nbsp;&nbsp;星际战争系列，Summer联盟。<BR>&nbsp;&nbsp;&nbsp;&nbsp;EZ_gx原创<BR> 
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
<tr><td>3 2
2 1 2
1 1 1
2 1 2
</td><td>3 3
</td></tr></table>
