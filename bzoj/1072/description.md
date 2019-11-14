
# Description

<div class="content"><p>　　给一个数字串s和正整数d, 统计s有多少种不同的排列能被d整除（可以有前导0）。例如123434有90种排列能<br/>
被2整除，其中末位为2的有30种，末位为4的有60种。</p></div>

# Input

<div class="content"><p>　　输入第一行是一个整数T，表示测试数据的个数，以下每行一组s和d，中间用空格隔开。s保证只包含数字0, 1<br/>
, 2, 3, 4, 5, 6, 7, 8, 9.</p></div>

# Output

<div class="content"><p>　　每个数据仅一行，表示能被d整除的排列的个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
000 1<br/>
001 1<br/>
1234567890 1<br/>
123434 2<br/>
1234 7<br/>
12345 17<br/>
12345678 29</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
3628800<br/>
90<br/>
3<br/>
6<br/>
1398</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">在前三个例子中，排列分别有1, 3, 3628800种，它们都是1的倍数。<br/><br/>
【限制】<br/><br/>
100%的数据满足：s的长度不超过10, 1&lt;=d&lt;=1000, 1&lt;=T&lt;=15<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

