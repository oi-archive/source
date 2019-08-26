
# Description

<div class="content"><p>给定一个长度为n的正整数序列a，每个数都在1到10^9范围内，告诉你其中s个数，并给出m条信息，每条信息包含三个数l,r,k以及接下来k个正整数，表示a[l],a[l+1],...,a[r-1],a[r]里这k个数中的任意一个都比任意一个剩下的r-l+1-k个数大（严格大于，即没有等号）。<br/>
请任意构造出一组满足条件的方案，或者判断无解。</p></div>

# Input

<div class="content"><p>第一行包含三个正整数n,s,m(1&lt;=s&lt;=n&lt;=100000，1&lt;=m&lt;=200000)。<br/>
接下来s行，每行包含两个正整数p[i],d[i](1&lt;=p[i]&lt;=n，1&lt;=d[i]&lt;=10^9)，表示已知a[p[i]]=d[i]，保证p[i]递增。<br/>
接下来m行，每行一开始为三个正整数l[i],r[i],k[i](1&lt;=l[i]&lt;r[i]&lt;=n，1&lt;=k[i]&lt;=r[i]-l[i])，接下来k[i]个正整数x[1],x[2],...,x[k[i]](l[i]&lt;=x[1]&lt;x[2]&lt;...&lt;x[k[i]]&lt;=r[i])，表示这k[i]个数中的任意一个都比任意一个剩下的r[i]-l[i]+1-k[i]个数大。<span style="font-family: Arial; font-size: 14px; line-height: 15.8666658401489px;">Σk &lt;= 300,000</span></p></div>

# Output

<div class="content"><p>若无解，则输出NIE。<br/>
否则第一行输出TAK，第二行输出n个正整数，依次输出序列a中每个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2 2<br/>
2 7<br/>
5 3<br/>
1 4 2 2 3<br/>
4 5 1 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
6 7 1000000000 6 3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

