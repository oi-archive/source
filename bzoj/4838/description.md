
# Description

<div class="content"><div>给定一个长度为n的非负整数序列a_1,a_2,?,a_n，你需要支持以下三种类型的操作：</div>
<div>1.给定l,r，满足1≤l≤r≤n，将a_l,a_(l+1),?,a_r依次修改为a_l^2,a_(l+1)^2,?,a_r^2。</div>
<div>2.给定l,r,x，满足1≤l≤r≤n,0≤x&lt;2017，将a_l,a_(l+1),?,a_r分别修改为x。</div>
<div>3.给定l,r，满足1≤l≤r≤n，统计a_l,a_(l+1),?,a_r在模2017意义下有多少个互不相同的数字。</div>
<div>现在按时间顺序给出m个操作，你需要给出第三种操作的结果。</div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数T，表示有T组数据，满足T≤200。</div>
<div>接下来依次给出每组测试数据。对于每组测试数据：</div>
<div>第一行包含两个正整数n和m，满足1≤n,m≤10^5。</div>
<div>第二行包含n个非负整数，表示a_1,a_2,?,a_n，满足0≤a_i&lt;2017。</div>
<div>接下来m行按时间顺序描述所有操作。每行表示一个操作，第一个整数是s，表示这是第s种操作，满足1≤s≤3，其他参数紧跟其后。</div>
<div>约10组数据满足n≥10^3或m≥10^3。</div>
<div></div>
<div></div></div>

# Output

<div class="content"><p>对于每个第三种操作，输出一行一个正整数表示答案。</p>
<div></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5 6<br/>
1 2 3 4 5<br/>
3 1 5<br/>
1 1 4<br/>
1 2 3<br/>
3 2 4<br/>
2 3 5 4<br/>
3 1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
2<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

