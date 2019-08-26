
# Description

<div class="content"><div id="pcont" style="margin-top: 20px">
<div class="pdsec"><span style="font-size: medium">问题描述</span></div>
<div class="pdcont"><span style="font-size: medium">　　你要对一个字符串进行三种操作：<br/>
　　0. 在位置x_i处插入一个字符串y_i<br/>
　　1. 删除位置[x_i, y_i)的字符串<br/>
　　2. 查询位置[x_i, y_i)的字符串包含多少次给定的子串z_i<br/>
</span></div>
</div></div>

# Input

<div class="content"><div class="pdcont"><span style="font-size: medium">　　第一行，一个整数T，表示操作个数。<br/>
　　下面T行，每行第一个数p_i，表示这个操作的类型：<br/>
　　若p_i=0，则接下来有一个整数x_i和一个字符串y_i，表示进行插入操作；<br/>
　　若p_i=1，则接下来有两个整数x_i和y_i，表示进行删除操作；<br/>
　　若p_i=2，则接下来有两个整数x_i和y_i，以及一个字符串z_i，表示进行询问。<br/>
　　字符串的下标从0开始(即第一个字符的下标为0)。<br/>
　　初始时字符串为空。<br/>
　　对于插入操作，插入后字符串y_i的首字符的下标应为x_i；<br/>
　　对于删除操作，删除的区间[x_i, y_i)为左闭右开区间；<br/>
　　对于查询操作，询问的区间[x_i, y_i)为左闭右开区间。<br/>
　　所有插入的和查询的字符串均不为空，且只包含0~9的字符。<br/>
　　所有询问的区间和删除的区间均不为空。<br/>
　　保证输入数据合法。<br/>
　　对于&#34;左闭右开区间&#34;不理解的可以去看样例解释。<br/>
</span></div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　对每个询问操作，输出一行，表示这个询问的答案。<br/>
</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
0 0 894894894<br/>
2 0 2 894<br/>
2 0 9 894<br/>
0 2 6<br/>
2 0 9 64<br/>
2 0 9 894<br/>
1 2 6<br/>
2 0 6 894<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
3<br/>
1<br/>
1<br/>
2<br/>
<br/>
样例说明<br/>
　　第一次操作后，字符串为894894894；<br/>
　　第二次操作，询问的区间为89，不包含任何894；<br/>
　　第三次操作，询问的区间为894894894，包含三个894；<br/>
　　第四次操作后，字符串为8964894894；<br/>
　　第五次操作，询问的区间为896489489，包含一个64；<br/>
　　第六次操作，询问的区间为896489489，包含一个894；<br/>
　　第七次操作后，字符串为894894；<br/>
　　第八次操作，询问的区间为894894，包含两个894。<br/>
<br/>
数据规模和约定<br/>
　　50%的数据中，询问个数&lt;=100 (不是操作个数)<br/>
　　100%的数据中，插入总长度&lt;=2000000，任何时刻字符串长度&lt;=1000000，插入次数&lt;=1001，删除次数&lt;=1000，询问的z_i的总长度&lt;=10000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

