<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Vasya是一位天生的Berland电影导演，他现在正在努力制作一部新的大片&#34;The Unexpected&#34; 。根据自己的经验，Vasya懂得为主角明智地选择一个名字(name)和姓氏(surname)是多么的重要。他制作了一个含有他想要使用的n个名字和n个姓氏的列表，但是Vasya还没有决定这些角色的具体姓名，所以他可以自由的将任何名字和姓氏匹配起来。现在，他需要以&#34;name_1 surname_1, name_2 surname_2, ..., name_n surname_n&#34;(即所有姓名之间用一个逗号一个空格隔开，名和姓之间用一个空格隔开)这样的格式写出一个含有所有主角的姓名的列表。首先Vasya想使名和姓的首字母相同的姓名对数最多，如果有多解，Vasya希望得到字典序最小的，帮帮他吧。<br/>
　　答案应该严格按照上述格式输出，包括逗号和空格，应保证输出的一行是所有可能的解中字典序最小的，行末不能有多余的逗号或空格。</div>
# 输入格式

<div class="pdcont">　　输入第一行是一个整数n ( 1 ≤ n ≤ 100 ) ，表示有n个name和n个surname。<br/>
　　接下来n行是name，再有n行是surname。<br/>
　　这2n个字符串中任意两个字符串都不同。每个name或者surname是一个不超过10个字母的非空字符串，保证首字母大写且剩余部分都是小写。</div>
# 输出格式

<div class="pdcont">　　输出应有一行，即所要求的列表，注意这一行要严格遵守输出格式。</div>
# 样例输入

<div class="pddata">样例输入1：<br/>
4<br/>
Ann<br/>
Anna<br/>
Sabrina<br/>
John<br/>
Petrov<br/>
Ivanova<br/>
Stoltz<br/>
Abacaba<br/>
<br/>
样例输入2：<br/>
4<br/>
Aa<br/>
Ab<br/>
Ac<br/>
Ba<br/>
Ad<br/>
Ae<br/>
Bb<br/>
Bc</div>
# 样例输出

<div class="pddata">样例输出1：<br/>
Ann Abacaba, Anna Ivanova, John Petrov, Sabrina Stoltz<br/>
<br/>
样例输出2：<br/>
Aa Ad, Ab Ae, Ac Bb, Ba Bc</div>
# 数据规模和约定

<div class="pdcont">　　对于 20% 数据保证所有字符串首字母一样。<br/>
　　对于 100% 数据保证 n ≤ 100 。</div>

</div>