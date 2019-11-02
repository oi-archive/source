# 

 
 # 题目背景 
小猫Rainbow：我好无聊T_T。<BR>小猫Freda：+1……T_T。<BR>小猫Rainbow：到我的城堡来玩吧lala~<BR>小猫Freda：好啊lala~ 

 
 # 题目描述 
&nbsp;&nbsp;Freda要到Rainbow的城堡去玩了。我们可以认为两座城堡位于同一条数轴上，Freda的城堡坐标是0，Rainbow的城堡坐标是N。正常情况下，Freda会朝着同一个方向（即Rainbow的城堡相对于Freda的城堡的方向）走若干步之后来到Rainbow的城堡，而且步长都为1或2。可是，今天Freda在途中遇见了来自上海的小猫Resodo，惊奇之下，居然有一步走反了方向！不过，Freda并没有神智不清，它只有一步走反了方向，而且这一步的步长也是1或2.&nbsp;同时，Freda并不会路过Rainbow的城堡而不停下来。当然，Freda是在途中遇到Resodo的，所以它不会在自己家门口就走错方向。<BR>&nbsp;举个例子，如果Rainbow的城堡坐标是3，那么下面两条路径是合法的：<BR>&nbsp;0-&gt;1-&gt;2-&gt;1-&gt;3<BR>&nbsp;0-&gt;1-&gt;-1-&gt;1-&gt;3<BR>&nbsp;当然，还有其它的合法路径。下面这些路径则是不合法的：<BR>&nbsp;0-&gt;-1-&gt;1-&gt;3&nbsp;（Freda不可能第一步就走错方向）<BR>&nbsp;0-&gt;1-&gt;3（Freda一定是有一步走错方向的）<BR>&nbsp;0-&gt;2-&gt;1-&gt;0-&gt;2-&gt;3（Freda只有一步是走错方向的）<BR>&nbsp;0-&gt;-1-&gt;0-&gt;3（Freda每步的长度一定是1或2）<BR>&nbsp;0-&gt;1-&gt;2-&gt;4-&gt;3（Freda不会越过Rainbow的城堡再回来）<BR>&nbsp;0&nbsp;-&gt;&nbsp;1&nbsp;-&gt;&nbsp;2&nbsp;-&gt;&nbsp;3&nbsp;-&gt;&nbsp;2&nbsp;-&gt;&nbsp;3（Freda一旦到达了Rainbow的城堡，就会停下来）<BR>你现在需要帮助Freda求出，它一共有多少种方法能够到达Rainbow的城堡呢？ 

 
 # 输入格式 
输入格式	<BR>&nbsp;&nbsp;&nbsp;&nbsp;一行一个整数N，表示Rainbow城堡的坐标。 

 
 # 输出格式 
输出格式<BR>&nbsp;&nbsp;&nbsp;&nbsp;一行一个整数，表示Freda到Rainbow城堡的不同路径数。由于这个数字可能很大，你只需要输出它mod&nbsp;1000000007的结果。 

 
 # 提示 
样例解释&nbsp;<BR>&nbsp;对于第一组样例，如下5条路径是合法的：<BR>&nbsp;0-&gt;1-&gt;0-&gt;2<BR>&nbsp;0-&gt;1-&gt;-1-&gt;0-&gt;1-&gt;2<BR>&nbsp;0-&gt;1-&gt;-1-&gt;0-&gt;2<BR>&nbsp;0-&gt;1-&gt;0-&gt;1-&gt;2<BR>&nbsp;0-&gt;1-&gt;-1-&gt;1-&gt;2<BR><BR>数据范围与约定<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于10%的数据，N&lt;=20.<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于70%的数据，N&lt;=1000.<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于90%的数据，N&lt;=1000000.<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，N&lt;=10^15.From&nbsp;-&nbsp;This_poet<BR>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<BR>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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

</td><td>5</td></tr></table>
