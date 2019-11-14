# 

 
 # 题目描述 
代数学研究的基本对象之一群是一些元素的集合。这些元素之间有一种代数运算，称之为乘法。两个群元素的乘积是一个群元素。一个大家习以为常的群是有理数乘法群，例如&nbsp;，&nbsp;等等，都是这个群中乘法的例子。需要注意的是，如果仅仅考虑有理数的乘法群，另外的一些运算比如加法是不被讨论的。数学家们把乘法抽象出来，就成为了群。群需要满足以下三条性质：<BR>结合律：对群中的任意元素a,b,c&nbsp;有&nbsp;a(bc)=(ab)c<BR>单位元：在群中存在唯一的元素e，它对群中任意的元素a有ea=a，ae=a<BR>有理数乘法群的单位元是1<BR>逆&nbsp;&nbsp;元：对群中任意元素a,都存在群中唯一的元素b,使得ab=ba=e<BR><BR>比如有理数乘法群中，23的逆元就为&nbsp;。从这里可以看出，整数乘法不能构成一个群<BR>需要注意的是，群的定义中并没有交换律，就是说ab不一定等于ba，有理数乘法群作为一个特例，其交换性是没有普遍的意义的<BR><BR>现在的问题是，给定群的元素的个数（群的阶数），需要知道这样的群有多少种。只要满足上述三条性质，就是群，应该算上。<BR>&nbsp;&nbsp;&nbsp;<BR>下面用四阶群的例子来说明这个问题。抽象地记群元素为e,a,b,c&nbsp;只要列出一个乘法表，就可以代表一个群。下面给出推导乘法表的步骤：<BR>群1	e	a	b	c<BR>e	e&nbsp;(1)	a&nbsp;(1)	b&nbsp;(1)	c&nbsp;(1)<BR>a	a&nbsp;(1)	e&nbsp;(2)	c&nbsp;(3)	b&nbsp;(3)<BR>b	b&nbsp;(1)	c&nbsp;(3)	e&nbsp;(4)	a&nbsp;(5)<BR>c	c&nbsp;(1)	b&nbsp;(3)	a&nbsp;(5)	e&nbsp;(5)<BR><BR>有单位元素的性质，可以填上<BR>a*a可能为e,b,c，但不可能为a,否则a*a=a两边乘以a的逆元，得到a=e；<BR>a*a=b和a*a=c的情况是一样的，只是乘法表中元素的位置进行了一个变换，本质没有改变，称为一个群同构；此时可以把a*a得到的元素称为b；<BR><BR>所以只要讨论a*a=e和a*a=b的情况；下面先讨论a*a=e的情况<BR>a*b不能为a或e，a*b为b的话，a=e，也矛盾，所以a*b=c；同理可填上所有的(3)<BR>b*b=e时，b*c=c*b=a，c*c=e，得到群1<BR>b*b=a时，b*c=c*b=e，c*c=a，得到群2<BR>群2	e	a	b	c<BR>e	e&nbsp;(1)	a&nbsp;(1)	b&nbsp;(1)	c&nbsp;(1)<BR>a	a&nbsp;(1)	e&nbsp;(2)	c&nbsp;(3)	b&nbsp;(3)<BR>b	b&nbsp;(1)	c&nbsp;(3)	a&nbsp;(4)	e&nbsp;(5)<BR>c	c&nbsp;(1)	b&nbsp;(3)	e&nbsp;(5)	a&nbsp;(5)<BR><BR>当a*a=b时，按照标号顺序可填出下列的群：<BR>群&nbsp;2’	e	a	b	c<BR>e	e&nbsp;(1)	a&nbsp;(1)	b&nbsp;(1)	c&nbsp;(1)<BR>a	a&nbsp;(1)	b&nbsp;(2)	c&nbsp;(4)	e&nbsp;(3)<BR>b	b&nbsp;(1)	c&nbsp;(4)	e&nbsp;(6)	a&nbsp;(5)<BR>c	c&nbsp;(1)	e&nbsp;(3)	a&nbsp;(5)	b&nbsp;(6)<BR><BR>但需要注意的是，这并没有得到一个新的群，把群2中的a,b调换位置，就得到了群2’。群2’只是群2的一个同构而已。<BR>综上所述，四阶群一共有2种。<BR><BR>虽然4阶群一定有交换律，但这里再次提醒，这并非一个普遍现象。<BR> 

 
 # 输入格式 
输入群的阶数n(4&lt;=n&lt;=3000)。&nbsp; 

 
 # 输出格式 
输出n阶群的种类数。 

 
 # 提示 
注意并灵活运用群的三条性质 
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
<tr><td>4</td><td>2</td></tr></table>
