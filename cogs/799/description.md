# 题目描述


<p>
【问题描述】
</p>
<p>
It is a well-known fact that behind every good comet is a UFO. These UFOs often come to collect loyal supporters from here on Earth. Unfortunately, they only have room to pick up one group of followers on each trip. They do, however, let the groups know ahead of time which will be picked up for each comet by a clever scheme: they pick a name for the comet which, along with the name of the group, can be used to determine if it is a particular group&#39;s turn to go (who do you think names the comets?). The details of the matching scheme are given below; your job is to write a program which takes the names of a group and a comet and then determines whether the group should go with the UFO behind that comet.
</p>
<p>
<img src="/upload/image/20131115/20131115133332_32847.jpg" alt=""/>
</p>
<p>
Both the name of the group and the name of the comet are converted into a number in the following manner: the final number is just the product of all the letters in the name, where &#34;A&#34; is 1 and &#34;Z&#34; is 26. For instance, the group &#34;USACO&#34; would be 21 * 19 * 1 * 3 * 15 = 17955. If the group&#39;s number mod 47 is the same as the comet&#39;s number mod 47, then you need to tell the group to get ready! (Remember that &#34;a mod b&#34; is the remainder left over after dividing a by b; 34 mod 10 is 4.)
</p>
<p>
Write a program which reads in the name of the comet and the name of the group and figures out whether according to the above scheme the names are a match, printing &#34;GO&#34; if they match and &#34;STAY&#34; if not. The names of the groups and the comets will be a string of capital letters with no spaces or punctuation, up to 6 characters long.
</p>
<p>
一个众所周知的事实，在每一慧星后面是一个不明飞行物UFO。 这些不明飞行物时常来收集来自在地球上忠诚的支持者。 不幸地，他们的空间在每次旅行只能带上一群支持者。 他们要做的是用一种聪明的方案让每一个团体人被慧星带走。他们为每个慧星起了一个名字，通过这些名字来决定一个团体是不是特定的慧星带走。 那个相配方案的细节在下面被给出； 你的工作要写一个程序来通过团体的名字和彗星的名字来决定一个组是否应该与在那一颗慧星后面的不明飞行物搭配。 团体的名字和慧星的名字都以下列各项方式转换成一个数字: 这个最后的数字代表名字中所有字母的信息，&#34;A&#34; 是 1 和 &#34;Z&#34; 是 26。 举例来说，团体 &#34;USACO&#34; 会是 21*19*1*3*15=17955 。 如果团体的数字除以mod 47的余数等于慧星的数字除以47的余数,那么你要告诉这个团体需要准备好被带走 ! 写一个程序读入慧星的名字和团体的名字，如果搭配打印&#34;GO&#34;否则打印&#34;STAY&#34; 团体的名字和慧星的名字将会是有没有空格或标点的一串大写字母（不超过6个字母）。 
</p>
<p>
<br/>
</p>
<p>
【输入】
</p>
<p>
输入文件 ride.in ，共 2 行。
</p>
<p>
Line 1:  An upper case character string of length 1..6 that is the name of the comet.
</p>
<p>
Line 2:  An upper case character string of length 1..6 that is the name of the group.
</p>
<p>
第 1 行: 彗星的名字（一个长度为1到6的字符串）
</p>
<p>
第 2 行: 团体的名字（一个长度为1到6的字符串）
</p>
<p>
【输出】
</p>
<p>
输出文件 ride.out ，仅 1 行。
</p>
<p>
A single line containing either the word &#34;GO&#34; or the word &#34;STAY&#34;.
</p>
<p>
单独一行包含&#34;STAY&#34;或&#34;GO&#34;.
</p>
<p>
【样例】
</p>
<p>
ride.in
</p>
<p>
COMETQ
</p>
<p>
HVNGAT
</p>
<p>
ride.out
</p>
<p>
GO
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
