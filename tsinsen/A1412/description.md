<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　任何一种生物的DNA都可以表示为一个由小写英文字母组成的非空字符串。科学家发现，所有的生物都有可能发生变异。所谓变异，就是子代的DNA串与父代的DNA串有差异。<br/>
　　每次变异，DNA串中恰好有一个字符会变成两个任意的字符。一共有n种可能的变异。变异ai-&gt;bici表示字符ai有可能变异为字符bici。每种变异都有可能发生任意多次。<br/>
　　如果有两种生物a,  b，他们的DNA串分别是s1,  s2，另外存在一种生物c，他的DNA串是s3。如果s3可以通过若干次变异变为s1，也可以通过若干次变异变为s2（请注意次数可以为0），那么生物c就被叫做生物a, b的公共祖先。<br/>
　　现在，给定两种生物，他们的DNA串分别是s1, s2。请找出他们的一个公共祖先，满足这个公共祖先的DNA串尽量短。</div>
# 输入格式

<div class="pdcont">　　第一行包含一个非空字符串s1，第二行包含一个非空字符串s2。这两个字符串的长度不会超过50。<br/>
　　第三行含有一个整数n(0&lt;=n&lt;=50)，表示所有可能的变异。<br/>
　　接下来n行，每行描述一种可能的变异，按照ai-&gt;bici的格式。<br/>
　　s1，s2，ai，bi，ci仅包含小写英文字母。<br/>
　　请注意：一种变异可能出现多次。</div>
# 输出格式

<div class="pdcont">　　如果这两种生物没有公共祖先，输出-1。<br/>
　　否则输出公共祖先DNA串的最短长度。</div>
# 样例输入

<div class="pddata">ababa<br/>
aba<br/>
2<br/>
c-&gt;ba<br/>
c-&gt;cc</div>
# 样例输出

<div class="pddata">2</div>
# 数据规模和约定

<div class="pdcont">　　输入串长度&lt;=50<br/>
　　N&lt;=50</div>

</div>