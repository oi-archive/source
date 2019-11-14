
# Description

<div class="content"><p><span style="font-size: medium">N个点m条边，每个点有一个点权a。<br/>
对于任意一个三元环(j，j，k)（i&lt;j&lt;k），它的贡献<br/>
为max(ai，aj，ak) <br/>
求所有三元环的贡献和。<br/>
N&lt;100000，，m&lt;250000。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">The first line of the standard input contains two integers  n and m (1&lt;=N&lt;=100000,1&lt;=M&lt;=250000) separated by a single space and denoting the number of confectioners at the convention and the number of pairs of them that like each other. The participants of the convention are numbered from  1 to N, The second line contains n integers pi (1&lt;=Pi&lt;=1000000) separated by single spaces and denoting the requirements of respective confectioners for flour (in decagrams). The following m lines contain data about pairs of contestants that like each other. Each of these lines contains two integers ai and bi (1&lt;=ai,bi&lt;=n Ai&lt;&gt;Bi) separated by a single space. They denote that confectioners ai and bi like each other. We assume that all pairs of participants of the convention apart from the ones listed in the input would not like to bake cakes together. Each pair of confectioners appears at most once in the input. <br/>
</span></p></div>

# Output

<div class="content"><p><font size="4">The first and only line of the standard output should contain a single integer - the quantity of flour that will be used by all teams in total, in decagrams. <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
1 5 3 4 2<br/>
1 2<br/>
2 3<br/>
5 2<br/>
4 3<br/>
3 1<br/>
1 4<br/>
5 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
Explanation of the example. The following three-person teams: (1,2,3),(1,2,5) and (1,3,4)require 5, 5 and 4 decagrams of flour to bake the cakes. In total 5+5+4=14 decagrams of flour are required. <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

