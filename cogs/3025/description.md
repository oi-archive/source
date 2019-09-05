# 题目描述


<h3>
【题目描述】
</h3>
<p>
Farmer John拥有一个传承数代的家族经营的农场，其中的奶牛的根源同样也可以在这个农场中追溯数代。通过检索古老的记录，Farmer John好奇于现在的这群奶牛互相之间是什么关系。请帮帮他！
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入的第一行包含N（1≤N≤100），之后是两头奶牛的名字。每头奶牛的名字都是由至多10个大写字母（A…Z）组成的字符串。Farmer John好奇于这行输入中这两头奶牛之间的关系。
</p>
<p>
接下来的N行，每行包含两头奶牛的名字X和Y，表示X是Y的母亲。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
输出包含一行，表示输入第一行指定的两头奶牛之间的关系（简单起见，在下面的例子中，将这两头奶牛称为BESSIE和ELSIE）。下面是可能出现的不同种类的关系：
</p>
<p>
<br/>
</p>
<p>
   <strong><u>**</u></strong>如果BESSIE和ELSIE的母亲是同一头奶牛，输出“SIBLINGS”。
</p>
<p>
   BESSIE可能是ELSIE的直系后代，也就是说ELSIE是BESSIE的母亲（mother），外祖母（grand-mother），外曾外祖母（great-grand-mother），外曾外曾外祖母（great-great-grand-mother），等等。如果是这种情况，输出“ELSIE is the (relation) of BESSIE&#34;，其中(relation)是适当的关系，比如“great-great-grand-mother”。
</p>
<p>
   <strong><u>**</u></strong>如果ELSIE不是BESSIE的某个祖先或姐妹，但是是BESSIE的某个祖先的孩子，那么ELSIE就是BESSIE的姨母（aunt）。（译者注：英语原题在这里表述有误，供题人已作出声明。）如果ELSIE是BESSIE的外祖母的孩子，输出“ELSIE is the aunt of BESSIE”；如果ELSIE是BESSIE的外曾外祖母的孩子，输出“ELSIE is the great-aunt of BESSIE”；如果ELSIE是BESSIE的外曾外曾外祖母的孩子，输出“ELSIE is the great-great-aunt of BESSIE”；以此类推。
</p>
<p>
   <strong><u>**</u></strong>如果BESSIE和ELSIE有任何其他的亲戚关系（也就是说，她们有共同的祖先），她们就是表姐妹，输出“COUSINS”。
</p>
<p>
   <strong><u>**</u></strong>如果BESSIE和ELSIE既没有共同的祖先，其中任何一头也不是另一头的直系后代，输出“NOT RELATED”。
</p>
<p>
<br/>
</p>
<p>
下图描述了上述关系，你只需考虑这些关系。观察到有一些像是“甥女（niece）”（姊妹的女儿）的关系是不必要的，这是由于如果BESSIE是ELSIE的甥女，那么ELSIE就是BESSIE的姨母。
</p>
<p>
<img src="/upload/image/20181025/20181025122316_92194.png" alt=""/> 
</p>
<h3>
【样例输入】
</h3>
<pre>7 AA BB
MOTHER AA
GGMOTHER BB
MOTHER SISTER
GMOTHER MOTHER
GMOTHER AUNT
AUNT COUSIN
GGMOTHER GMOTHER
</pre>
<h3>
【样例输出】
</h3>
<pre>BB is the great-aunt of AA</pre>
<h3>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://www.usaco.org/index.php?page=open18results" target="_blank">USACO 2018 OPEN CONTEST</a> BRONZE Problem 3 Family Tree
</p>
<p>
供题：Brian Dean
</p>
