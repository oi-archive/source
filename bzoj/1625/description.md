
# Description

<div class="content"><p><span style="font-size: medium">贝茜在珠宝店闲逛时，买到了一个中意的手镯。很自然地，她想从她收集的 N(1 &lt;= N &lt;= 3,402)块宝石中选出最好的那些镶在手镯上。对于第i块宝石，它的重量为W_i(1 &lt;= W_i &lt;= 400)，并且贝茜知道它在镶上手镯后能为自己增加的魅力值D_i(1 &lt;= D_i &lt;= 100)。由于贝茜只能忍受重量不超过M(1 &lt;= M &lt;= 12,880)的手镯，她可能无法把所有喜欢的宝石都镶上。 于是贝茜找到了你，告诉了你她所有宝石的属性以及她能忍受的重量，希望你能帮她计算一下，按照最合理的方案镶嵌宝石的话，她的魅力值最多能增加多少。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 2个用空格隔开的整数：N 和 M </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 第i+1行为2个用空格隔开的整数：W_i、D_i，分别为第i块宝石 的重量与能为贝茜增加的魅力值 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出1个整数，表示按照镶嵌要求，贝茜最多能增加的魅力值 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 6<br/>
1 4<br/>
2 6<br/>
3 12<br/>
2 7<br/>
<br/>
输入说明:<br/>
<br/>
    贝茜收集了4块宝石，她能忍受重量最大为6的手镯。<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">23<br/>
<br/>
输出说明:<br/>
<br/>
    贝茜把除了第二块宝石的其余所有宝石都镶上手镯，这样她能增加<br/>
4+12+7=23的魅力值，并且所有宝石的重量为1+2+3 &lt;= 6，同样符合要求。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

