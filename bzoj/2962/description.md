
# Description

<div class="content"><p><span style="font-size: medium">　　有一个长度为n的序列，有三个操作1.I a b c表示将[a,b]这一段区间的元素集体增加c，2.R a b表示将[a,b]区间内所有元素变成相反数，3.Q a b c表示询问[a,b]这一段区间中选择c个数相乘的所有方案的和mod 19940417的值。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　第一行两个数n，q表示序列长度和操作个数。<br/>
　　第二行n个非负整数，表示序列。<br/>
　　接下来q行每行输入一个操作I a b c或者 R a b或者Q a b c意义如题目描述。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">　　对于每个询问，输出选出c个数相乘的所有方案的和mod19940417的值。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2 3 4 5<br/>
I 2 3 1<br/>
Q 2 4 2<br/>
R 1 5<br/>
I 1 3 -1<br/>
Q 1 5 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">40<br/>
19940397<br/>
样例说明<br/>
　　做完第一个操作序列变为1 3 4 4 5。<br/>
　　第一次询问结果为3*4+3*4+4*4=40。<br/>
　　做完R操作变成-1 -3 -4 -4 -5。<br/>
　　做完I操作变为-2 -4 -5 -4 -5。<br/>
　　第二次询问结果为-2-4-5-4-5=-20。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>　　100%的数据n&lt;=50000,q&lt;=50000,初始序列的元素的绝对值&lt;=109，I a b c中保证[a,b]是一个合法区间，|c|&lt;=109，R a b保证[a,b]是个合法的区间。Q a b c中保证[a,b]是个合法的区间1&lt;=c&lt;=min(b-a+1,20)。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=中国国家队清华集训 2012-2013 第三天
">中国国家队清华集训 2012-2013 第三天<br/>
</a></p></div>

