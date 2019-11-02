# 

 
 # 题目背景 
SCOI2011&nbsp;Day1&nbsp;第一题 

 
 # 题目描述 
幼儿园里有N个小朋友，lxhgww老师现在想要给这些小朋友们分配糖果，要求每个小朋友都要分到糖果。但是小朋友们也有嫉妒心，总是会提出一些要求，比如小明不希望小红分到的糖果比他的多，于是在分配糖果的时候，lxhgww需要满足小朋友们的K个要求。幼儿园的糖果总是有限的，lxhgww想知道他至少需要准备多少个糖果，才能使得每个小朋友都能够分到糖果，并且满足小朋友们所有的要求。 

 
 # 输入格式 
输入的第一行是两个整数N，K。<BR>接下来K行，表示这些点需要满足的关系，每行3个数字，X，A，B。<BR>如果X=1，&nbsp;表示第A个小朋友分到的糖果必须和第B个小朋友分到的糖果一样多；<BR>如果X=2，&nbsp;表示第A个小朋友分到的糖果必须少于第B个小朋友分到的糖果；<BR>如果X=3，&nbsp;表示第A个小朋友分到的糖果必须不少于第B个小朋友分到的糖果；<BR>如果X=4，&nbsp;表示第A个小朋友分到的糖果必须多于第B个小朋友分到的糖果；<BR>如果X=5，&nbsp;表示第A个小朋友分到的糖果必须不多于第B个小朋友分到的糖果；<BR><BR> 

 
 # 输出格式 
输出一行，表示lxhgww老师至少需要准备的糖果数，如果不能满足小朋友们的所有要求，就输出-1。 

 
 # 提示 
对于30%的数据，保证&nbsp;N&lt;=100<BR>对于100%的数据，保证&nbsp;N&lt;=100000<BR>对于所有的数据，保证&nbsp;K&lt;=100000，1&lt;=X&lt;=5，1&lt;=A,&nbsp;B&lt;=N<BR> 
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
<tr><td>5 7
1 1 2
2 3 2
4 4 1
3 4 5
5 4 5
2 3 5
4 5 1
</td><td>11</td></tr></table>
