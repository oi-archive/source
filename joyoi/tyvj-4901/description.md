# 

 
 # 题目背景 
<p style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">（本题难度约为NOIP联赛普及组第一题，适合即将参加NOIP的选手们练练手）</p>

<p style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">（P.S.因作者水平有限，题目可能会有小bug，请多多谅解）</p>

<p style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">今天是clz的生日，clz好开心好开心哇&mdash;&mdash;因为晚上将会有好多他的好盆友来参加他的生日宴会！为了迎接朋友们的到来，clz在家中的n个位置上分别挂上了数量不一的气球（编号依次为1~n）。clz非常喜欢偶数，他觉得偶数是自然界中最美妙的数，因为&ldquo;好事成双&rdquo;嘛。现在clz希望在这n堆气球中，第i堆到第j堆的气球总数的和总是偶数（i&le;j且i,j为任意1~n间的自然数），你能帮他判断一下现在家中布置的气球是否满足clz的要求吗？</p> 

 
 # 题目描述 
<p>输入正整数n，以及n个数组成的数列，即每个位置上气球的个数。判断其气球的布置是否满足clz的要求，如果满足，输出&ldquo;Right&rdquo;，否则输出&ldquo;Wrong&rdquo;（不包括引号）。</p> 

 
 # 输入格式 
<p>第一行一个正整数n，第二行为n个自然数a[1],a[2],&hellip;&hellip;,a[n]，其中a[i]表示编号为i的位置上气球的个数。</p> 

 
 # 输出格式 
<p>如果符合要求，输出&ldquo;Right&rdquo;，否则输出&ldquo;Wrong&rdquo;（不包括引号）。</p> 

 
 # 提示 
<p>【输入样例】</p>

<p>6</p>

<p>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6</p>

<p>【输出样例】</p>

<p>Wrong</p>

<p>【样例解释】</p>

<p>位置1到2上的气球和为奇数，不满足要求。</p>

<p>【数据范围】</p>

<p>50%的数据，1&le;n&le;10^4，1&le;a[i]&le;10^9</p>

<p>100%的数据，1&le;n&le;10^5，1&le;a[i]&le;10^100。</p> 
