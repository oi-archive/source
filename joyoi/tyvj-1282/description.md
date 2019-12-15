# 

 
 # 题目背景 
吃晚饭，作为人类生命活动中非常重要的一环，一直倍受DL重视。不幸运的是，每次DL和Xm同车的时候，他们都要很晚才有晚饭吃，甚至没晚饭吃。因此，DL称Xm作"晚饭克星"。当然，Xm不是很爽，他觉得有点委屈。为此，他决定调查出谁才是真正的晚饭克星。<BR> 

 
 # 题目描述 
Xm发现，晚饭克星必定是存在于车中，车上的人可以看成是围成一个圈的，Xm按顺时针顺序给他们编了号1~N。Xm发现，每个人都会有一个&nbsp;灭晚饭系数K。当然，每个人的K值可能不相同。<BR><img src="/source/joyoi/tyvj-1282/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI4Mi9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL3AxMjgyLmpwZw==.jpg" border=0 align=middle>	&nbsp;<BR>	我们可以在K值和小写字母间建立关系。上图是两种合法的情况。图A描述了将k=1对应a的情况，图B则是将k=2对应a。图A中k=1（即⑥）对应了a，那么k=2(即⑦)就对应了b，k=5（即①)对应了e，以此类推。&nbsp;图B则是另一种对应方式：K=2对应了a，k=5对应了f，k=7对应了h。。。这时，K=1没有对应。&nbsp;<BR>	在确定对应关系后，可以顺时针按顺序选出若干个字符，如果满足以下条件，就称为一个"晚饭克星组合"。：<BR>1．	全部字符按顺序构成字符串M='dinnerkillers'。<BR>2．	如果第i个人对应M[x],第j个人对应M[x+1],那么i+1~j-1个人中没有任何一个人可以对应M[x+1].<BR>3．	最后人在第一个人的逆时针方向。<BR>我们就称选出的人构成了一个"晚饭克星组合"。<BR>可能有多种对应，每种对应也可能存在多个晚饭克星组合，如果某两个组合中存在一个相同位置的字母对应的人不同，就认为是不同的组合。组成最多的晚饭克星组合的人，就认为是晚饭克星。如果有多个，则按编号大小全部输出。<BR><BR> 

 
 # 输入格式 
输入文件第一行是一个数字N，表示共有N个人。<BR>	接下来有N行，每行一个整数，代表第i个人的K值。<BR><BR> 

 
 # 输出格式 
输出每个所有的晚饭克星的编号，每行一个。如果没有就输出'NONE'。<BR> 

 
 # 提示 
让97对应'A'可以对应成：<BR>iinnerkillersSdd<BR>然后从最后的d开始，顺时针选出（这是一个圈）：<BR>iinnerkillersSdd<BR>iinnerkillersSdd<BR>则第1、3~13均有两个组合经过，15~16只有一个，第2、14个人没有。<BR>Ps：<BR>1.	其他对应方式也一起加起来算，但是这个样例只有这种对应方式存在组合。<BR>2.	第二i如果选出会与条件二矛盾，故他不能构成一个组合。<BR><BR><BR>对于40%的数据，N&lt;255。<BR>对于100%的数据，N&lt;5000。<BR><BR> 
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
<tr><td>16
105
105
110
110
101
114
107
105
108
108
101
114
115
83
100
100

</td><td>1
3
4
5
6
7
8
9
10
11
12
13

</td></tr></table>
