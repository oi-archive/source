# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;Milesian是一个很受这个学校女生喜欢的男生。在这个学校每两个女生直接或间接的存在有且只有一个联系。根据这个联系，我们把每个女生当做一个点。直接联系的两个女生之间，连一条边。每个女生对milesian都有个诱惑值。<BR>&nbsp;&nbsp;&nbsp;&nbsp;如果milesian同时与直接联系的两个女生聊天。那么就相当于和与这两个女生有间接联系的女生聊天(=&nbsp;=)这个时候，这两个直接联系的两个女生间所连的边会断开）。于是，milesian将受到来自两边所有女生的诱惑，也就是说，一边女生的诱惑值是这一边女生所有诱惑值之和。当然，两边诱惑值之差的绝对值越小，milesian就会越清醒.<BR>这样，对他参加NOI2011有很大的好处，但是现在，milesian的双手，正被女生们拉扯着。他需要你的帮助！！！帮助他吧。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;问题化简后就是这样的一个问题了：给定一个N个点的树。树上每一个点都有一个固定的权值Ai。同样，每一条边也有一个权值。边的权值就是删去这条边后，形成的两个联通块的每一个联通块上的点的总和后的两个联通块的差取绝对值。<BR>&nbsp;&nbsp;&nbsp;&nbsp;求权值最小的边。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行输入一个数，N，为女生们的总人数<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二行有N个正整数，其中Ai，表示第i个女生的诱惑值。中间用一个空格隔开<BR>&nbsp;&nbsp;&nbsp;&nbsp;以下N-1行，每行有两个小于等于N，且互不相等的正整数A,B。表示A,B这两个女生有直接联系<BR>&nbsp;&nbsp;&nbsp;&nbsp;(N&lt;=100000,Ai和Bi均为&lt;100000的正整数) 

 
 # 输出格式 
只有一个数。为milesian所受两边诱惑值的差的绝对值的最小值 
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
<tr><td>5
7 7 7 7 7
1 3
2 3
4 3
5 3</td><td>21</td></tr></table>
