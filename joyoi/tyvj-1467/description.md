# 

 
 # 题目背景 
&nbsp;&nbsp;Candy住在一个被划分为n个区域的神奇小镇中，其中Candy的家在编号为n的区域，Candy生日这天，大家都急急忙忙赶去Candy家庆祝Candy的生日。 

 
 # 题目描述 
&nbsp;&nbsp;Candy共有t个朋友住在不同的区域。小镇有m条道路，小镇的神奇之处在于其中的p1条道路只会在你走过区域的的个数为奇数时候开启，p2道路只会在你走过区域的个数为偶数的时候开启，剩下的道路一直都会开启。并且，所有的道路只能够单向通过。飘飘乎居士希望知道在所有的好朋友中，谁离Candy最近?。<BR> 

 
 # 输入格式 
第一行：两个正整数n&nbsp;m，表示共n个区域，m条道路<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来m行，每行三个正整数u&nbsp;v&nbsp;s表示u到v的单向道路，路程为s，其中第i条道路的编号为i。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接着一个整数p1以及p1个正整数odd[i]，表示编号为odd[i]的道路只会在走过奇数个区域时开启。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接着一个整数p2以及p2个正整数even[i]，表示编号为even[i]的道路只会在走过偶数个区域时开启。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一个正整数&nbsp;t<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;紧接着t行，每行一个正整数h以及一个不超过10个字符长度的字符串na（且均有小写字母组成），表示在h区域居住着名字为na的人。<BR><BR> 

 
 # 输出格式 
第一行，即距离candy家最近的人的名字，数据保证有且只有一个人为最后的答案。&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<BR>第二行，该人到candy家的距离。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果存在多解，则输入名字中字典序较小的一人。<BR><BR> 

 
 # 提示 
pink尽管从1-&gt;3-&gt;4距离更近，但因为1-&gt;2的这条道路只有在走过奇数个区域时才开启，而pink此时走过的区域为偶数个（0个）（我们规定，出发点不算走第一个区域），所以pink只好沿1—&gt;2—&gt;3—&gt;4，距离为5；<BR>Violethill尽管沿2—&gt;3—&gt;4距离为3，但因为3—&gt;4这条道路只有在走过偶数个区域时才开启，当violethill从2到3时，只走了奇数个（1个）区域，道路不会开启。所以，violethill只好沿2—&gt;4这条道路行走，距离为4，所以violethill比pink更快到candy家中，并且距离为4。<BR>对于30%的数据&nbsp;0&lt;n&lt;=100<BR>对于100%的数据0&lt;n&lt;=10000&nbsp;&nbsp;&nbsp;0&lt;m&lt;=100000<BR>对于所有数据保证两区域间的距离&lt;=100000<BR>数据保证运算即结果在maxlongint以内<BR>数据保证输入的正确性，即至少有一个人可以到达candy家中，并且一个区域最多只有一人，不会出现相同名字的人。<BR>友情提示：可能出现有些道路既在odd中出现，也在even中出现。并且odd或者even中的数都可能出现重复数字。<BR> 
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
<tr><td>4 5
1 2 2
3 4 2
2 4 4
1 3 1
2 3 1
1 4 
1 2
2
2 violethill
1 pink

</td><td>violethill
4</td></tr></table>
