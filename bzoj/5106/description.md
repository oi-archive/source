
# Description

<div class="content"><div>有n棵树，初始时每棵树的高度为Hi，第i棵树每月都会长高Ai。现在有个木料长度总量为S的订单，客户要求每块</div>
<div>木料的长度不能小于L，而且木料必须是整棵树（即不能为树的一部分）。现在问你最少需要等多少个月才能满足</div>
<div>订单。</div>
<p></p></div>

# Input

<div class="content"><div>第一行3个用空格隔开的非负整数n,S,L，表示树的数量、订单总量和单块木料长</div>
<div>度限制。</div>
<div>第二行n个用空格隔开的非负整数，依次为H1,H2,...,Hn。</div>
<div>第三行n个用空格隔开的非负整数，依次为A1,A2,...,An。</div>
<div>1&lt;=N&lt;=200000,1&lt;=S,L&lt;=10^18,1&lt;=Hi,Ai&lt;=10^9</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数表示答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 74 51<br/>
2 5 2<br/>
2 7 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
【 Hints】<br/>
对于样例，在六个月后，各棵树的高度分别为 14, 47, 56，此时无法完成订单。在七个月后，各棵树的高度分别<br/>
为 16, 54, 65，此时可以砍下第 2 和第 3 棵树完成订单了。</span></div>

# Hint

<div class="content"><p></p><div>来自 CodePlus 2017 11 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。</div><br/>
<div>Credit：idea/郑林楷　命题/郑林楷　验题/王聿中</div><br/>
<div>Git Repo：https://git.thusaac.org/publish/CodePlus201711</div><br/>
<div>本次比赛的官方网址：cp.thusaac.org</div><br/>
<div>感谢腾讯公司对此次比赛的支持。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

