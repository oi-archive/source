
# Description

<div class="content"><p><span style="font-size: medium">某天WJMZBMR学习了一个神奇的算法：树的点分治！<br/>
这个算法的核心是这样的：<br/>
消耗时间=0<br/>
Solve(树 a)<br/>
 消耗时间 += a 的 大小<br/>
 如果 a 中 只有 1 个点<br/>
  退出<br/>
 否则在a中选一个点x，在a中删除点x<br/>
 那么a变成了几个小一点的树，对每个小树递归调用Solve<br/>
我们注意到的这个算法的时间复杂度跟选择的点x是密切相关的。<br/>
如果x是树的重心，那么时间复杂度就是O(nlogn)<br/>
但是由于WJMZBMR比较傻逼，他决定随机在a中选择一个点作为x！<br/>
Sevenkplus告诉他这样做的最坏复杂度是O(n^2)<br/>
但是WJMZBMR就是不信&gt;_&lt;。。。<br/>
于是Sevenkplus花了几分钟写了一个程序证明了这一点。。。你也试试看吧^_^<br/>
现在给你一颗树，你能告诉WJMZBMR他的傻逼算法需要的期望消耗时间吗？（消耗时间按在Solve里面的那个为标准）</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个整数n，表示树的大小<br/>
接下来n-1行每行两个数a,b，表示a和b之间有一条边<br/>
注意点是从0开始标号的</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一行一个浮点数表示答案<br/>
四舍五入到小数点后4位<br/>
如果害怕精度跪建议用long double或者extended</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 1<br/>
1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">5.6667</span></div>

# Hint

<div class="content"><p></p><p>n&lt;=30000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=我们都爱GYZ杯">我们都爱GYZ杯</a></p></div>

