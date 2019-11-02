# 

 
 # 题目背景 
NOIP&nbsp;2012&nbsp;普及组&nbsp;题2 

 
 # 题目描述 
传说很遥远的藏宝楼顶层藏着诱人的宝藏。小明历尽千辛万苦终于找到传说中的这个藏&nbsp;宝楼，藏宝楼的门口竖着一个木板，上面写有几个大字：寻宝说明书。说明书的内容如下：&nbsp;藏宝楼共有&nbsp;N+1&nbsp;层，最上面一层是顶层，顶层有一个房间里面藏着宝藏。除了顶层外，&nbsp;藏宝楼另有&nbsp;N&nbsp;层，每层&nbsp;M&nbsp;个房间，这&nbsp;M&nbsp;个房间围成一圈并按逆时针方向依次编号为&nbsp;0，…，&nbsp;M-1。其中一些房间有通往上一层的楼梯，每层楼的楼梯设计可能不同。每个房间里有一个&nbsp;指示牌，指示牌上有一个数字&nbsp;x，表示从这个房间开始按逆时针方向选择第&nbsp;x&nbsp;个有楼梯的房&nbsp;间（假定该房间的编号为&nbsp;k），从该房间上楼，上楼后到达上一层的&nbsp;k&nbsp;号房间。比如当前房&nbsp;间的指示牌上写着&nbsp;2，则按逆时针方向开始尝试，找到第&nbsp;2&nbsp;个有楼梯的房间，从该房间上楼。&nbsp;如果当前房间本身就有楼梯通向上层，该房间作为第一个有楼梯的房间。<br><br>寻宝说明书的最后用红色大号字体写着：“寻宝须知：帮助你找到每层上楼房间的指示&nbsp;牌上的数字（即每层第一个进入的房间内指示牌上的数字）总和为打开宝箱的密钥”。<br><br>请帮助小明算出这个打开宝箱的密钥。 

 
 # 输入格式 
第一行&nbsp;2&nbsp;个整数&nbsp;N&nbsp;和&nbsp;M，之间用一个空格隔开。N&nbsp;表示除了顶层外藏宝楼共&nbsp;N&nbsp;层楼，M&nbsp;表示除顶层外每层楼有&nbsp;M&nbsp;个房间。<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来&nbsp;N*M&nbsp;行，每行两个整数，之间用一个空格隔开，每行描述一个房间内的情况，&nbsp;其中第(i-1)*M+j&nbsp;行表示第&nbsp;i&nbsp;层&nbsp;j-1&nbsp;号房间的情况（i=1,&nbsp;2,&nbsp;…,&nbsp;N；j=1,&nbsp;2,&nbsp;…&nbsp;,M）。第一个整数&nbsp;表示该房间是否有楼梯通往上一层（0&nbsp;表示没有，1&nbsp;表示有），第二个整数表示指示牌上的数&nbsp;字。注意，从&nbsp;j&nbsp;号房间的楼梯爬到上一层到达的房间一定也是&nbsp;j&nbsp;号房间。<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;最后一行，一个整数，表示小明从藏宝楼底层的几号房间进入开始寻宝（注：房间编号&nbsp;从&nbsp;0&nbsp;开始）。 

 
 # 输出格式 
输出只有一行，一个整数，表示打开宝箱的密钥，这个数可能会很大，请输出对&nbsp;20123取模的结果即可。 

 
 # 提示 
【输入输出样例说明】<br><br><br>第一层：<br><br>0&nbsp;号房间，有楼梯通往上层，指示牌上的数字是&nbsp;2；<br><br>1&nbsp;号房间，无楼梯通往上层，指示牌上的数字是&nbsp;3；<br><br>2&nbsp;号房间，有楼梯通往上层，指示牌上的数字是&nbsp;4；<br><br>第二层：<br><br>0&nbsp;号房间，无楼梯通往上层，指示牌上的数字是&nbsp;1；<br><br>1&nbsp;号房间，有楼梯通往上层，指示牌上的数字是&nbsp;5；<br><br>2&nbsp;号房间，有楼梯通往上层，指示牌上的数字是&nbsp;2；<br><br>小明首先进入第一层（底层）的&nbsp;1&nbsp;号房间，记下指示牌上的数字为&nbsp;3，然后从这个房间&nbsp;开始，沿逆时针方向选择第&nbsp;3&nbsp;个有楼梯的房间&nbsp;2&nbsp;号房间进入，上楼后到达第二层的&nbsp;2&nbsp;号房间，&nbsp;记下指示牌上的数字为&nbsp;2，由于当前房间本身有楼梯通向上层，该房间作为第一个有楼梯的&nbsp;房间。因此，此时沿逆时针方向选择第&nbsp;2&nbsp;个有楼梯的房间即为&nbsp;1&nbsp;号房间，进入后上楼梯到达&nbsp;顶层。这时把上述记下的指示牌上的数字加起来，即&nbsp;3+2=5，所以打开宝箱的密钥就是&nbsp;5。<br><br>【数据范围】<br><br>对于&nbsp;50%数据，有&nbsp;0&lt;N≤1000，0&lt;x≤10000；<br><br>对于&nbsp;100%数据，有&nbsp;0&lt;N≤10000，0&lt;M≤100，0&lt;x≤1,000,000；NOIP&nbsp;2012 
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
<tr><td>2 3
1 2
0 3
1 4
0 1
1 5
1 2
1</td><td>5</td></tr></table>
