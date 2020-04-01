
# Description

<div class="content"><img border="0" src="/source/bzoj/1871/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4NzEuanBn.jpg"/> </div>

# Input

<div class="content">输入文件的第一行为一个整数 N(N ≤ 10)和 M(1 ≤ M ≤ 1000)，表示属性集中
的属性个数和函数依赖集中的依赖个数。这里我们默认大写字母中的前 N 个字
母为我们所考虑的属性。接下来的 M 行每行一个字符串表示一个函数依赖，如
AB--&gt;DE。(中间的蕴含符号是由减号和大于号组成。另外需要说明的是，只有当
我们同时得到 A和 B 的时候，才能推出D和 E） 。 
</div>

# Output

<div class="content">第一行希望你输出你找到的候选码的个数K。 接下来的 K行每行
输出一个候选码。候选码本身按字母顺序排列，所有候选码按照字典顺序排列输
出。如果没有找到候选码，输出“No candidate key”(不含引号)。 
 </div>

# Sample Input

<div class="content"><span class="sampledata">5 5 <br/>
AB-&gt;C <br/>
AC-&gt;B <br/>
AD-&gt;E <br/>
BC-&gt;D <br/>
E-&gt;A <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 <br/>
AB <br/>
AC <br/>
BE <br/>
CE <br/>
</span></div>

# Hint

<div class="content"><p>对于30%的测试数据，满足只有二元联系(即不存在函数依赖左边或右边的<br/>
属性个数超过 1 个)。 <br/>
对于 40%的测试数据，满足N ≤ 5。 <br/>
对于 70%的测试数据，满足M ≤ 100。 <br/>
对于100%的测试数据，满足 1 ≤ N ≤ 10, 1 ≤ M ≤ 1000。 <br/>
 </p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

